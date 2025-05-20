# Function: <code>fanotify_handle_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *fanotify_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81252a40)
Location: fs/notify/fanotify/fanotify.c:187
Inline: True
```
**Symbols:**

```
ffffffff81252a40-ffffffff81252d5f: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *fanotify_mark, u32 mask, void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8127b200)
Location: fs/notify/fanotify/fanotify.c:176
Inline: True
```
**Symbols:**

```
ffffffff8127b200-ffffffff8127b4d3: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *fanotify_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8128edb0)
Location: fs/notify/fanotify/fanotify.c:176
Inline: True
```
**Symbols:**

```
ffffffff8128edb0-ffffffff8128f07b: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *fanotify_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8129bc20)
Location: fs/notify/fanotify/fanotify.c:184
Inline: True
```
**Symbols:**

```
ffffffff8129bc20-ffffffff8129bf00: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, struct fsnotify_mark *inode_mark, struct fsnotify_mark *fanotify_mark, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff812bf030)
Location: fs/notify/fanotify/fanotify.c:174
Inline: True
```
**Symbols:**

```
ffffffff812bf030-ffffffff812bf389: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff812e7fa0)
Location: fs/notify/fanotify/fanotify.c:180
Inline: True
```
**Symbols:**

```
ffffffff812e7fa0-ffffffff812e82e6: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const unsigned char *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff812fcc40)
Location: fs/notify/fanotify/fanotify.c:193
Inline: False
```
**Symbols:**

```
ffffffff812fcc40-ffffffff812fcfc0: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8131d890)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffff8131d890-ffffffff8131dcee: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813306d0)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffff813306d0-ffffffff81330b2e: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8136acc0)
Location: fs/notify/fanotify/fanotify.c:494
Inline: False
```
**Symbols:**

```
ffffffff8136acc0-ffffffff8136ae92: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81378140)
Location: fs/notify/fanotify/fanotify.c:648
Inline: False
```
**Symbols:**

```
ffffffff81378140-ffffffff8137845b: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137ed00)
Location: fs/notify/fanotify/fanotify.c:711
Inline: False
```
**Symbols:**

```
ffffffff8137ed00-ffffffff8137f073: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813cbde0)
Location: fs/notify/fanotify/fanotify.c:711
Inline: False
```
**Symbols:**

```
ffffffff813cbde0-ffffffff813cc04b: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814543e0)
Location: fs/notify/fanotify/fanotify.c:885
Inline: False
```
**Symbols:**

```
ffffffff814543e0-ffffffff81454697: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e32a0)
Location: fs/notify/fanotify/fanotify.c:888
Inline: False
```
**Symbols:**

```
ffffffff814e32a0-ffffffff814e3553: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:892
Inline: False
```
**Symbols:**

```
ffffffff81519bc0-ffffffff81519e92: fanotify_handle_event (STB_LOCAL)
ffffffff820e9e78-ffffffff820e9eaa: fanotify_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:878
Inline: False
```
**Symbols:**

```
ffffffff8154dfa0-ffffffff8154e263: fanotify_handle_event (STB_LOCAL)
ffffffff821c692d-ffffffff821c695f: fanotify_handle_event.cold (STB_LOCAL)
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
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffff8000103ed8c8)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffff8000103ed8c8-ffff8000103edd48: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (c05c412c)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
c05c412c-c05c4614: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (c0000000004f50a0)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
c0000000004f50a0-c0000000004f56b8: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffe0002a12d0)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffe0002a12d0-ffffffe0002a1706: fanotify_handle_event (STB_LOCAL)
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
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81328cb0)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffff81328cb0-ffffffff8132910e: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81319850)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffff81319850-ffffffff81319cae: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81326780)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffff81326780-ffffffff81326bde: fanotify_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fanotify_handle_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813385a0)
Location: fs/notify/fanotify/fanotify.c:374
Inline: False
```
**Symbols:**

```
ffffffff813385a0-ffffffff813389f5: fanotify_handle_event (STB_LOCAL)
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
<code>struct fsnotify_mark *fanotify_mark</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, inode, inode_mark, fanotify_mark, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>group, inode, mask, data, data_type, file_name, cookie, iter_info</code>
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
<code>struct inode *dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, inode, mask, data, data_type, file_name, cookie, iter_info</code> ➡️ <code>group, mask, data, data_type, dir, file_name, cookie, iter_info</code>
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
