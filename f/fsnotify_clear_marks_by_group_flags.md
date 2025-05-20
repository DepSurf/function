# Function: <code>fsnotify_clear_marks_by_group_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group_flags(struct fsnotify_group *group, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250a70)
Location: fs/notify/mark.c:430
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_clear_inode_marks_by_group
  - fs/notify/mark.c:fsnotify_clear_marks_by_group
  - fs/notify/vfsmount_mark.c:fsnotify_clear_vfsmount_marks_by_group
```
**Symbols:**

```
ffffffff81250a70-ffffffff81250b7d: fsnotify_clear_marks_by_group_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group_flags(struct fsnotify_group *group, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81279110)
Location: fs/notify/mark.c:453
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_clear_inode_marks_by_group
  - fs/notify/vfsmount_mark.c:fsnotify_clear_vfsmount_marks_by_group
```
**Symbols:**

```
ffffffff81279110-ffffffff8127922c: fsnotify_clear_marks_by_group_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group_flags(struct fsnotify_group *group, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128cd40)
Location: fs/notify/mark.c:453
Inline: False
Direct callers:
  - fs/notify/inode_mark.c:fsnotify_clear_inode_marks_by_group
  - fs/notify/vfsmount_mark.c:fsnotify_clear_vfsmount_marks_by_group
```
**Symbols:**

```
ffffffff8128cd40-ffffffff8128ce56: fsnotify_clear_marks_by_group_flags (STB_GLOBAL)
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
