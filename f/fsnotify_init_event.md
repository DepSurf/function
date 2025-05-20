# Function: <code>fsnotify_init_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8124fc90)
Location: fs/notify/notification.c:207
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff8124fc90-ffffffff8124fca9: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812783b0)
Location: fs/notify/notification.c:198
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff812783b0-ffffffff812783c9: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8128c0c0)
Location: fs/notify/notification.c:209
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff8128c0c0-ffffffff8128c0d9: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81299050)
Location: fs/notify/notification.c:209
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff81299050-ffffffff81299069: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812bc3f0)
Location: fs/notify/notification.c:209
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff812bc3f0-ffffffff812bc409: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812e5010)
Location: fs/notify/notification.c:210
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff812e5010-ffffffff812e5029: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_init_event(struct fsnotify_event *event, struct inode *inode, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812f9b30)
Location: fs/notify/notification.c:210
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff812f9b30-ffffffff812f9b49: fsnotify_init_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8131c07c)
Location: include/linux/fsnotify_backend.h:500
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8131c363)
Location: include/linux/fsnotify_backend.h:500
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8131d659)
Location: include/linux/fsnotify_backend.h:500
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132ee5c)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8132f133)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81330499)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81368d66)
Location: include/linux/fsnotify_backend.h:529
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8136929a)
Location: include/linux/fsnotify_backend.h:529
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8136aa3e)
Location: include/linux/fsnotify_backend.h:529
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813760fa)
Location: include/linux/fsnotify_backend.h:578
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137657a)
Location: include/linux/fsnotify_backend.h:578
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_new_group
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81377cd2)
Location: include/linux/fsnotify_backend.h:578
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81378aa3)
Location: include/linux/fsnotify_backend.h:578
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8137ca9a)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137ce93)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e831)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f580)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff813c999a)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813c9d43)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb911)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc53f)
Location: include/linux/fsnotify_backend.h:584
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8145141f)
Location: include/linux/fsnotify_backend.h:747
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81451818)
Location: include/linux/fsnotify_backend.h:747
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8145404b)
Location: include/linux/fsnotify_backend.h:747
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454cfe)
Location: include/linux/fsnotify_backend.h:747
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814dff0f)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e0518)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2efb)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3bf4)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff815167ab)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81516dc8)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815196f0)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a555)
Location: include/linux/fsnotify_backend.h:824
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8154ab9b)
Location: include/linux/fsnotify_backend.h:819
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154b1b8)
Location: include/linux/fsnotify_backend.h:819
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154dad0)
Location: include/linux/fsnotify_backend.h:819
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e925)
Location: include/linux/fsnotify_backend.h:819
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffff8000103eb9b0)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffff8000103ebd34)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffff8000103ed6b4)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (c05c28b0)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (c05c2e04)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (c05c3e94)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (c0000000004f2e48)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (c0000000004f372c)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (c0000000004f4d94)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fc58)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffe00029ff7e)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a10f0)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8132743c)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81327713)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81328a79)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81317fdc)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813182b3)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81319619)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81324f0c)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813251e3)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81326549)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81336cec)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff81337583)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81338369)
Location: include/linux/fsnotify_backend.h:502
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
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
</ul>
