# Function: <code>dnotify_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff812511f0)
Location: fs/notify/dnotify/dnotify.c:84
Inline: False
```
**Symbols:**

```
ffffffff812511f0-ffffffff812512a8: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff812799f0)
Location: fs/notify/dnotify/dnotify.c:84
Inline: False
```
**Symbols:**

```
ffffffff812799f0-ffffffff81279aa7: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff8128d5a0)
Location: fs/notify/dnotify/dnotify.c:84
Inline: False
```
**Symbols:**

```
ffffffff8128d5a0-ffffffff8128d657: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff8129a4b0)
Location: fs/notify/dnotify/dnotify.c:80
Inline: False
```
**Symbols:**

```
ffffffff8129a4b0-ffffffff8129a567: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *vfsmount_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff812bd890)
Location: fs/notify/dnotify/dnotify.c:80
Inline: False
```
**Symbols:**

```
ffffffff812bd890-ffffffff812bd947: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff812e6540)
Location: fs/notify/dnotify/dnotify.c:80
Inline: False
```
**Symbols:**

```
ffffffff812e6540-ffffffff812e6611: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff812fb0d0)
Location: fs/notify/dnotify/dnotify.c:81
Inline: False
```
**Symbols:**

```
ffffffff812fb0d0-ffffffff812fb1a1: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/dnotify/dnotify.c (0)
Location: fs/notify/dnotify/dnotify.c:72
Inline: False
```
**Symbols:**

```
ffffffff8131b9a0-ffffffff8131ba86: dnotify_handle_event (STB_LOCAL)
ffffffff8131bf0e-ffffffff8131bf21: dnotify_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff8132e760)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff8132e760-ffffffff8132e841: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81368640)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff81368640-ffffffff81368720: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81375970)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff81375970-ffffffff81375a3e: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff8137c310)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff8137c310-ffffffff8137c3de: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff813c9110)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff813c9110-ffffffff813c9221: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81450a30)
Location: fs/notify/dnotify/dnotify.c:91
Inline: False
```
**Symbols:**

```
ffffffff81450a30-ffffffff81450b3f: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff814df480)
Location: fs/notify/dnotify/dnotify.c:91
Inline: False
```
**Symbols:**

```
ffffffff814df480-ffffffff814df58f: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81515d10)
Location: fs/notify/dnotify/dnotify.c:91
Inline: False
```
**Symbols:**

```
ffffffff81515d10-ffffffff81515e1f: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_mark *inode_mark, u32 mask, struct inode *inode, struct inode *dir, const struct qstr *name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff8154a0d0)
Location: fs/notify/dnotify/dnotify.c:90
Inline: False
```
**Symbols:**

```
ffffffff8154a0d0-ffffffff8154a1df: dnotify_handle_event (STB_LOCAL)
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
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffff8000103eb0d8)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffff8000103eb0d8-ffff8000103eb20c: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (c05c21b0)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
c05c21b0-c05c22c4: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (c0000000004f2350)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
c0000000004f2350-c0000000004f24d0: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffe00029f534)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffe00029f534-ffffffe00029f652: dnotify_handle_event (STB_LOCAL)
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
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81326d40)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff81326d40-ffffffff81326e21: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff813178e0)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff813178e0-ffffffff813179c1: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81324810)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff81324810-ffffffff813248f1: dnotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dnotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/dnotify/dnotify.c (ffffffff81336590)
Location: fs/notify/dnotify/dnotify.c:73
Inline: False
```
**Symbols:**

```
ffffffff81336590-ffffffff8133666f: dnotify_handle_event (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_mark *inode_mark</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param added. </b>
<code>const struct qstr *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_group *group</code>
</li>
<li>
<b>Param removed. </b>
<code>const void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>int data_type</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct qstr *file_name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_iter_info *iter_info</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, inode, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>inode_mark, mask, inode, dir, name, cookie</code>
</li>
</ul>
</details>
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
