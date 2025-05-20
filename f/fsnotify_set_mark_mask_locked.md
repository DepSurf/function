# Function: <code>fsnotify_set_mark_mask_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_set_mark_mask_locked(struct fsnotify_mark *mark, __u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250680)
Location: fs/notify/mark.c:245
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_mark_add_to_mask
  - fs/notify/fanotify/fanotify_user.c:fanotify_mark_remove_from_mask
```
**Symbols:**

```
ffffffff81250680-ffffffff812506a3: fsnotify_set_mark_mask_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_set_mark_mask_locked(struct fsnotify_mark *mark, __u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278d00)
Location: fs/notify/mark.c:267
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_mark_add_to_mask
  - fs/notify/fanotify/fanotify_user.c:fanotify_mark_remove_from_mask
```
**Symbols:**

```
ffffffff81278d00-ffffffff81278d23: fsnotify_set_mark_mask_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_set_mark_mask_locked(struct fsnotify_mark *mark, __u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c930)
Location: fs/notify/mark.c:267
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_mark_add_to_mask
  - fs/notify/fanotify/fanotify_user.c:fanotify_mark_remove_from_mask
```
**Symbols:**

```
ffffffff8128c930-ffffffff8128c953: fsnotify_set_mark_mask_locked (STB_GLOBAL)
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
