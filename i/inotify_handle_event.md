# Function: <code>inotify_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81251750)
Location: fs/notify/inotify/inotify_fsnotify.c:65
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81251750-ffffffff812518a5: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81279f40)
Location: fs/notify/inotify/inotify_fsnotify.c:65
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81279f40-ffffffff8127a090: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8128daf0)
Location: fs/notify/inotify/inotify_fsnotify.c:65
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8128daf0-ffffffff8128dc40: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8129aa30)
Location: fs/notify/inotify/inotify_fsnotify.c:66
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8129aa30-ffffffff8129ab7b: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812bde40)
Location: fs/notify/inotify/inotify_fsnotify.c:66
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff812bde40-ffffffff812bdf8b: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812e6ae0)
Location: fs/notify/inotify/inotify_fsnotify.c:66
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff812e6ae0-ffffffff812e6c6a: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff812fb670)
Location: fs/notify/inotify/inotify_fsnotify.c:67
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff812fb670-ffffffff812fb844: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8131c264-ffffffff8131c279: inotify_handle_event.cold (STB_LOCAL)
ffffffff8131bf90-ffffffff8131c18e: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132ed70)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff8132ed70-ffffffff8132ef72: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368c60)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81368c60-ffffffff81368e6c: inotify_handle_event (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eb8e8)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffff8000103eb8e8-ffff8000103ebad8: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (c05c27b4)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
c05c27b4-c05c2a04: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2d50)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
c0000000004f2d50-c0000000004f3008: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fb98)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffe00029fb98-ffffffe00029fd62: inotify_handle_event (STB_GLOBAL)
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
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81327350)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81327350-ffffffff81327552: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81317ef0)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81317ef0-ffffffff813180f2: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324e20)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81324e20-ffffffff81325022: inotify_handle_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336c00)
Location: fs/notify/inotify/inotify_fsnotify.c:58
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_ignored_and_remove_idr
```
**Symbols:**

```
ffffffff81336c00-ffffffff81336e02: inotify_handle_event (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *data</code> ➡️ <code>const void *data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_iter_info *iter_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fsnotify_mark *inode_mark</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_mark *vfsmount_mark</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, inode, inode_mark, vfsmount_mark, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>group, inode, mask, data, data_type, file_name, cookie, iter_info</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const unsigned char *file_name</code> ➡️ <code>const struct qstr *file_name</code>
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
