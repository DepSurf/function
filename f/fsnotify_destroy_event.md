# Function: <code>fsnotify_destroy_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8124f9d0)
Location: fs/notify/notification.c:70
Inline: False
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8124f9d0-ffffffff8124fa19: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81278120)
Location: fs/notify/notification.c:70
Inline: False
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81278120-ffffffff8127816c: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8128be00)
Location: fs/notify/notification.c:70
Inline: False
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8128be00-ffffffff8128be6e: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81299006)
Location: fs/notify/notification.c:70
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81298d50-ffffffff81298d9f: fsnotify_destroy_event.part.3 (STB_LOCAL)
ffffffff81298dd0-ffffffff81298df0: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff812bc3a6)
Location: fs/notify/notification.c:70
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff812bc0e0-ffffffff812bc135: fsnotify_destroy_event.part.3 (STB_LOCAL)
ffffffff812bc170-ffffffff812bc190: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff812e4fc6)
Location: fs/notify/notification.c:70
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff812e4d00-ffffffff812e4d55: fsnotify_destroy_event.part.6 (STB_LOCAL)
ffffffff812e4d90-ffffffff812e4daf: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff812f9ae6)
Location: fs/notify/notification.c:70
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff812f9820-ffffffff812f9875: fsnotify_destroy_event.part.6 (STB_LOCAL)
ffffffff812f98b0-ffffffff812f98cf: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8131a196)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81319e90-ffffffff81319ee5: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffff8131a1d1-ffffffff8131a1e4: fsnotify_destroy_event.part.0.cold (STB_LOCAL)
ffffffff81319f20-ffffffff81319f3f: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8132cfc6)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8132ccc0-ffffffff8132cd15: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffff8132cd50-ffffffff8132cd6f: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81366a70)
Location: fs/notify/notification.c:57
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81366a70-ffffffff81366ad4: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81373dc0)
Location: fs/notify/notification.c:57
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81373dc0-ffffffff81373e24: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8137a6f0)
Location: fs/notify/notification.c:50
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8137a6f0-ffffffff8137a754: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff813c7370)
Location: fs/notify/notification.c:50
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff813c7370-ffffffff813c73d4: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8144e750)
Location: fs/notify/notification.c:50
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8144e750-ffffffff8144e7c9: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff814dce80)
Location: fs/notify/notification.c:50
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_write
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff814dce80-ffffffff814dcef9: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff815136e0)
Location: fs/notify/notification.c:50
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff815136e0-ffffffff81513759: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81547b70)
Location: fs/notify/notification.c:50
Inline: True
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_inode_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81547b70-ffffffff81547be9: fsnotify_destroy_event (STB_GLOBAL)
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
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffff8000103e8ca4)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffff8000103e87e0-ffff8000103e8890: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffff8000103e8918-ffff8000103e895c: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (c05c04bc)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
c05c00a4-c05c0128: fsnotify_destroy_event.part.0 (STB_LOCAL)
c05c017c-c05c01ac: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (c0000000004ef7e0)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:finish_permission_event
```
**Symbols:**

```
c0000000004ef240-c0000000004ef310: fsnotify_destroy_event.part.0 (STB_LOCAL)
c0000000004ef350-c0000000004ef378: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffe00029d826)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffe00029d434-ffffffe00029d4c0: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffe00029d4fa-ffffffe00029d536: fsnotify_destroy_event (STB_GLOBAL)
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
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff813255a6)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff813252a0-ffffffff813252f5: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffff81325330-ffffffff8132534f: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81316146)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81315e40-ffffffff81315e95: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffff81315ed0-ffffffff81315eef: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81323076)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81322d70-ffffffff81322dc5: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffff81322e00-ffffffff81322e1f: fsnotify_destroy_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_destroy_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81334db6)
Location: fs/notify/notification.c:57
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_flush_notify
Direct callers:
  - fs/notify/notification.c:fsnotify_flush_notify
  - fs/notify/inotify/inotify_fsnotify.c:inotify_handle_event
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/inotify/inotify_user.c:inotify_read
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81334aa0-ffffffff81334af3: fsnotify_destroy_event.part.0 (STB_LOCAL)
ffffffff81334b40-ffffffff81334b5f: fsnotify_destroy_event (STB_GLOBAL)
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
