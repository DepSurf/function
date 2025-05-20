# Function: <code>fsnotify_find_vfsmount_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/vfsmount_mark.c (ffffffff81250cf0)
Location: fs/notify/vfsmount_mark.c:71
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
```
**Symbols:**

```
ffffffff81250cf0-ffffffff81250d36: fsnotify_find_vfsmount_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/vfsmount_mark.c (ffffffff812794f0)
Location: fs/notify/vfsmount_mark.c:71
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff812794f0-ffffffff81279536: fsnotify_find_vfsmount_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fsnotify_mark *fsnotify_find_vfsmount_mark(struct fsnotify_group *group, struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/vfsmount_mark.c (ffffffff8128d0b0)
Location: fs/notify/vfsmount_mark.c:71
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_vfsmount_mark
  - fs/notify/fanotify/fanotify_user.c:fanotify_remove_vfsmount_mark
```
**Symbols:**

```
ffffffff8128d0b0-ffffffff8128d0f6: fsnotify_find_vfsmount_mark (STB_GLOBAL)
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
