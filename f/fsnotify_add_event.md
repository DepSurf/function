# Function: <code>fsnotify_add_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8124fa20)
Location: fs/notify/notification.c:87
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
**Symbols:**

```
ffffffff8124fa20-ffffffff8124fb53: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81278170)
Location: fs/notify/notification.c:88
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
**Symbols:**

```
ffffffff81278170-ffffffff812782be: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8128be70)
Location: fs/notify/notification.c:97
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
**Symbols:**

```
ffffffff8128be70-ffffffff8128bfb1: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81298df0)
Location: fs/notify/notification.c:97
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
**Symbols:**

```
ffffffff81298df0-ffffffff81298f35: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812bc190)
Location: fs/notify/notification.c:97
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
**Symbols:**

```
ffffffff812bc190-ffffffff812bc2d7: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812e4db0)
Location: fs/notify/notification.c:97
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
```
**Symbols:**

```
ffffffff812e4db0-ffffffff812e4eff: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff812f98d0)
Location: fs/notify/notification.c:97
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff812f98d0-ffffffff812f9a1f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81319f40)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81319f40-ffffffff8131a08f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8132cd70)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8132cd70-ffffffff8132cebf: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81366ae0)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81366ae0-ffffffff81366c2f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81373e30)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81373e30-ffffffff81373f7f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct fsnotify_group *, struct fsnotify_event *), void (*insert)(struct fsnotify_group *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8137a760)
Location: fs/notify/notification.c:81
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8137a760-ffffffff8137a8c1: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct fsnotify_group *, struct fsnotify_event *), void (*insert)(struct fsnotify_group *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (0)
Location: fs/notify/notification.c:81
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81cc546f-ffffffff81cc548a: fsnotify_add_event.cold (STB_LOCAL)
ffffffff813c73e0-ffffffff813c754b: fsnotify_add_event (STB_GLOBAL)
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81451446)
Location: include/linux/fsnotify_backend.h:621
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8145462e)
Location: include/linux/fsnotify_backend.h:621
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff814dff36)
Location: include/linux/fsnotify_backend.h:622
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e34ea)
Location: include/linux/fsnotify_backend.h:622
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff81516800)
Location: include/linux/fsnotify_backend.h:622
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff81519e15)
Location: include/linux/fsnotify_backend.h:622
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/inotify/inotify_fsnotify.c (ffffffff8154abf0)
Location: include/linux/fsnotify_backend.h:622
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154e1ef)
Location: include/linux/fsnotify_backend.h:622
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffff8000103e8960)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffff8000103e8960-ffff8000103e8b04: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (c05c01ac)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
c05c01ac-c05c033c: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (c0000000004ef380)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
c0000000004ef380-c0000000004ef5fc: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffe00029d536)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffe00029d536-ffffffe00029d6e6: fsnotify_add_event (STB_GLOBAL)
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
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81325350)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81325350-ffffffff8132549f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81315ef0)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81315ef0-ffffffff8131603f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81322e20)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81322e20-ffffffff81322f6f: fsnotify_add_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fsnotify_add_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct list_head *, struct fsnotify_event *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81334b60)
Location: fs/notify/notification.c:84
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81334b60-ffffffff81334ca9: fsnotify_add_event (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*insert)(struct fsnotify_group *, struct fsnotify_event *)</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*merge)(struct list_head *, struct fsnotify_event *)</code> ➡️ <code>int (*merge)(struct fsnotify_group *, struct fsnotify_event *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
