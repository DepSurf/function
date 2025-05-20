# Function: <code>fsnotify_notify_queue_is_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8124f990)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8124f990-ffffffff8124f99b: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff8124f9a0-ffffffff8124f9c2: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81278358)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff812780e0-ffffffff812780eb: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff812780f0-ffffffff81278115: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8128c055)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff8128bdc0-ffffffff8128bdcb: fsnotify_notify_queue_is_empty.part.2 (STB_LOCAL)
ffffffff8128bdd0-ffffffff8128bdf4: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81298fd5)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff81298d40-ffffffff81298d4b: fsnotify_notify_queue_is_empty.part.2 (STB_LOCAL)
ffffffff81298da0-ffffffff81298dc4: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff812bc375)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff812bc0d0-ffffffff812bc0db: fsnotify_notify_queue_is_empty.part.2 (STB_LOCAL)
ffffffff812bc140-ffffffff812bc164: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff812e4fa1)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff812e4cf0-ffffffff812e4cfb: fsnotify_notify_queue_is_empty.part.5 (STB_LOCAL)
ffffffff812e4d60-ffffffff812e4d84: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff812f9ac1)
Location: fs/notify/notification.c:64
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff812f9810-ffffffff812f981b: fsnotify_notify_queue_is_empty.part.5 (STB_LOCAL)
ffffffff812f9880-ffffffff812f98a4: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8131a171)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff81319e70-ffffffff81319e7b: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff81319ef0-ffffffff81319f14: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8132cfa1)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff8132cca0-ffffffff8132ccab: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff8132cd20-ffffffff8132cd44: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81366d11)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/inotify/inotify_user.c:get_one_event
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
  - fs/notify/fanotify/fanotify_user.c:get_one_event
```
**Symbols:**

```
ffffffff81366a40-ffffffff81366a62: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81374061)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/inotify/inotify_user.c:get_one_event
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
  - fs/notify/fanotify/fanotify_user.c:get_one_event
```
**Symbols:**

```
ffffffff81373d90-ffffffff81373db2: fsnotify_notify_queue_is_empty (STB_GLOBAL)
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
In fs/notify/notification.c (ffffffff8137aa01)
Location: include/linux/fsnotify_backend.h:497
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8137d31e)
Location: include/linux/fsnotify_backend.h:497
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8138004e)
Location: include/linux/fsnotify_backend.h:497
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
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
In fs/notify/notification.c (ffffffff813c7671)
Location: include/linux/fsnotify_backend.h:497
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff813ca39e)
Location: include/linux/fsnotify_backend.h:497
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813ccfbe)
Location: include/linux/fsnotify_backend.h:497
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
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
In fs/notify/notification.c (ffffffff8144eab3)
Location: include/linux/fsnotify_backend.h:640
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814515ae)
Location: include/linux/fsnotify_backend.h:640
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145476e)
Location: include/linux/fsnotify_backend.h:640
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
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
In fs/notify/notification.c (ffffffff814dd233)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff814e009e)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e364e)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
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
In fs/notify/notification.c (ffffffff81513a8f)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8151695e)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81519f8e)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
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
In fs/notify/notification.c (ffffffff81547f1f)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/notification.c:fsnotify_remove_first_event
```
```
In fs/notify/inotify/inotify_user.c (ffffffff8154ad4e)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_poll
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e35e)
Location: include/linux/fsnotify_backend.h:641
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffff8000103e8c80)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffff8000103e87b0-ffff8000103e87c4: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffff8000103e88d8-ffff8000103e8918: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (c05c0478)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
c05c008c-c05c00a4: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
c05c0140-c05c017c: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (c0000000004ef77c)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
c0000000004ef310-c0000000004ef344: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffe00029d7f6)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffe00029d420-ffffffe00029d434: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffe00029d4c0-ffffffe00029d4fa: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81325581)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff81325280-ffffffff8132528b: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff81325300-ffffffff81325324: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81316121)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff81315e20-ffffffff81315e2b: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff81315ea0-ffffffff81315ec4: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81323051)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff81322d50-ffffffff81322d5b: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff81322dd0-ffffffff81322df4: fsnotify_notify_queue_is_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fsnotify_notify_queue_is_empty(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81334d93)
Location: fs/notify/notification.c:51
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_poll
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_poll
```
**Symbols:**

```
ffffffff81334a90-ffffffff81334a9b: fsnotify_notify_queue_is_empty.part.0 (STB_LOCAL)
ffffffff81334b10-ffffffff81334b34: fsnotify_notify_queue_is_empty (STB_GLOBAL)
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
