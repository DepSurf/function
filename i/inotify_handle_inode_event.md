# Function: <code>inotify_handle_inode_event</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81376030)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81376030-ffffffff81376239: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8137c9d0)
Location: fs/notify/inotify/inotify_fsnotify.c:59
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8137c9d0-ffffffff8137cbd4: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813c98d0)
Location: fs/notify/inotify/inotify_fsnotify.c:59
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff813c98d0-ffffffff813c9ad4: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81451350)
Location: fs/notify/inotify/inotify_fsnotify.c:59
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81451350-ffffffff81451561: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814dfe40)
Location: fs/notify/inotify/inotify_fsnotify.c:59
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff814dfe40-ffffffff814e004d: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff815166c0)
Location: fs/notify/inotify/inotify_fsnotify.c:59
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff815166c0-ffffffff8151690a: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inotify_handle_inode_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8154aab0)
Location: fs/notify/inotify/inotify_fsnotify.c:59
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8154aab0-ffffffff8154acfa: inotify_handle_inode_event (STB_GLOBAL)
```
</details>
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
