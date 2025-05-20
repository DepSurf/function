# Function: <code>fanotify_alloc_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct inode *inode, u32 mask, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81252960)
Location: fs/notify/fanotify/fanotify.c:153
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
**Symbols:**

```
ffffffff81252960-ffffffff81252a39: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct inode *inode, u32 mask, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8127b120)
Location: fs/notify/fanotify/fanotify.c:142
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
**Symbols:**

```
ffffffff8127b120-ffffffff8127b1f9: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct inode *inode, u32 mask, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8128ecd0)
Location: fs/notify/fanotify/fanotify.c:142
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
**Symbols:**

```
ffffffff8128ecd0-ffffffff8128eda9: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct inode *inode, u32 mask, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8129bb40)
Location: fs/notify/fanotify/fanotify.c:150
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
**Symbols:**

```
ffffffff8129bb40-ffffffff8129bc1f: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct inode *inode, u32 mask, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff812bef50)
Location: fs/notify/fanotify/fanotify.c:142
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
**Symbols:**

```
ffffffff812bef50-ffffffff812bf02f: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff812e7eb0)
Location: fs/notify/fanotify/fanotify.c:139
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812e7eb0-ffffffff812e7fa0: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fanotify_event_info *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff812fcae0)
Location: fs/notify/fanotify/fanotify.c:144
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff812fcae0-ffffffff812fcc3c: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff8131dcee-ffffffff8131dd12: fanotify_alloc_event.cold (STB_LOCAL)
ffffffff8131d550-ffffffff8131d88d: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff81330b2e-ffffffff81330b52: fanotify_alloc_event.cold (STB_LOCAL)
ffffffff81330390-ffffffff813306cd: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, const struct qstr *file_name, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8136a950)
Location: fs/notify/fanotify/fanotify.c:347
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
**Symbols:**

```
ffffffff8136a950-ffffffff8136acb2: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81377b50)
Location: fs/notify/fanotify/fanotify.c:521
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81377b50-ffffffff81377f6f: fanotify_alloc_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137e5e0)
Location: fs/notify/fanotify/fanotify.c:566
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8137e5e0-ffffffff8137eb17: fanotify_alloc_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813cb6c0)
Location: fs/notify/fanotify/fanotify.c:566
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff813cb6c0-ffffffff813cbbf7: fanotify_alloc_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid, u32 match_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81453c30)
Location: fs/notify/fanotify/fanotify.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81453c30-ffffffff814543d1: fanotify_alloc_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid, u32 match_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e2ae0)
Location: fs/notify/fanotify/fanotify.c:706
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff814e2ae0-ffffffff814e3281: fanotify_alloc_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid, u32 match_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff815193c0)
Location: fs/notify/fanotify/fanotify.c:710
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff815193c0-ffffffff81519baf: fanotify_alloc_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, __kernel_fsid_t *fsid, u32 match_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154d7a0)
Location: fs/notify/fanotify/fanotify.c:704
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8154d7a0-ffffffff8154df8f: fanotify_alloc_event (STB_LOCAL)
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
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffff8000103ed5e8)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
```
**Symbols:**

```
ffff8000103ed5e8-ffff8000103ed8c8: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (c05c3dbc)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
**Symbols:**

```
c05c3dbc-c05c412c: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (c0000000004f4ca0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
**Symbols:**

```
c0000000004f4ca0-c0000000004f5094: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffe0002a1052)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
```
**Symbols:**

```
ffffffe0002a1052-ffffffe0002a12d0: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff8132910e-ffffffff81329132: fanotify_alloc_event.cold (STB_LOCAL)
ffffffff81328970-ffffffff81328cad: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff81319cae-ffffffff81319cd2: fanotify_alloc_event.cold (STB_LOCAL)
ffffffff81319510-ffffffff8131984d: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff81326bde-ffffffff81326c02: fanotify_alloc_event.cold (STB_LOCAL)
ffffffff81326440-ffffffff8132677d: fanotify_alloc_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct fanotify_event *fanotify_alloc_event(struct fsnotify_group *group, struct inode *inode, u32 mask, const void *data, int data_type, __kernel_fsid_t *fsid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
```
**Symbols:**

```
ffffffff813389f5-ffffffff81338a19: fanotify_alloc_event.cold (STB_LOCAL)
ffffffff81338260-ffffffff8133859d: fanotify_alloc_event (STB_GLOBAL)
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
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fsnotify_group *group</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, mask, path</code> ➡️ <code>group, inode, mask, path</code>
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
<b>Param added. </b>
<code>const void *data</code>
</li>
<li>
<b>Param added. </b>
<code>int data_type</code>
</li>
<li>
<b>Param added. </b>
<code>__kernel_fsid_t *fsid</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct fanotify_event_info *</code> ➡️ <code>struct fanotify_event *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct qstr *file_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>group, inode, mask, data, data_type, fsid</code> ➡️ <code>group, inode, mask, data, data_type, file_name, fsid</code>
</li>
</ul>
</details>
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
<code>group, inode, mask, data, data_type, file_name, fsid</code> ➡️ <code>group, mask, data, data_type, dir, file_name, fsid</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 match_mask</code>
</li>
</ul>
</details>
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
