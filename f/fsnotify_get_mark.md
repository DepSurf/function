# Function: <code>fsnotify_get_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812503f0)
Location: fs/notify/mark.c:99
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
Direct callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812503f0-ffffffff812503ff: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8127925c)
Location: fs/notify/mark.c:103
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_group_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_destroy_marks
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81278ae0-ffffffff81278aef: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128ce86)
Location: fs/notify/mark.c:103
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_detach_group_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group_flags
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_destroy_marks
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff8128c710-ffffffff8128c71f: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812997c0)
Location: fs/notify/mark.c:106
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812997c0-ffffffff812997da: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bcc40)
Location: fs/notify/mark.c:106
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812bcc40-ffffffff812bcc60: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e57b0)
Location: fs/notify/mark.c:106
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:untag_chunk
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff812e57b0-ffffffff812e57d0: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812fa330)
Location: fs/notify/mark.c:106
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff812fa330-ffffffff812fa350: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131ad30)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff8131ad30-ffffffff8131ad50: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d8a0)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff8132d8a0-ffffffff8132d8c0: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367960)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff81367960-ffffffff813679ad: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374cc0)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff81374cc0-ffffffff81374d0d: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137b680)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff8137b680-ffffffff8137b6cd: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c8430)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
**Symbols:**

```
ffffffff813c8430-ffffffff813c847d: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f9a0)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
**Symbols:**

```
ffffffff8144f9a0-ffffffff8144fa17: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814de290)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
**Symbols:**

```
ffffffff814de290-ffffffff814de307: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514ac0)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
**Symbols:**

```
ffffffff81514ac0-ffffffff81514b37: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81548ea0)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
**Symbols:**

```
ffffffff81548ea0-ffffffff81548f17: fsnotify_get_mark (STB_GLOBAL)
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
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9df8)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffff8000103e9df8-ffff8000103e9e44: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c1348)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
c05c1348-c05c13ac: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f1b2c)
Location: fs/notify/mark.c:94
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
c0000000004f0e70-c0000000004f0eb8: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029f028)
Location: fs/notify/mark.c:94
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffe00029e758-ffffffe00029e79e: fsnotify_get_mark (STB_GLOBAL)
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
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81325e80)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff81325e80-ffffffff81325ea0: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316a20)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff81316a20-ffffffff81316a40: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323950)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff81323950-ffffffff81323970: fsnotify_get_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_get_mark(struct fsnotify_mark *mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335690)
Location: fs/notify/mark.c:94
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:prune_tree_chunks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/inotify/inotify_user.c:inotify_idr_find_locked
```
**Symbols:**

```
ffffffff81335690-ffffffff813356b0: fsnotify_get_mark (STB_GLOBAL)
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
