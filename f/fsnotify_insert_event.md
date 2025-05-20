# Function: <code>fsnotify_insert_event</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fsnotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct fsnotify_group *, struct fsnotify_event *), void (*insert)(struct fsnotify_group *, struct fsnotify_event *));
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
ffffffff81e77e77-ffffffff81e77e92: fsnotify_insert_event.cold (STB_LOCAL)
ffffffff8144e7d0-ffffffff8144e94c: fsnotify_insert_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fsnotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct fsnotify_group *, struct fsnotify_event *), void (*insert)(struct fsnotify_group *, struct fsnotify_event *));
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
ffffffff82069e87-ffffffff82069ea2: fsnotify_insert_event.cold (STB_LOCAL)
ffffffff814dcf10-ffffffff814dd08c: fsnotify_insert_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fsnotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct fsnotify_group *, struct fsnotify_event *), void (*insert)(struct fsnotify_group *, struct fsnotify_event *));
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
ffffffff820e9d4f-ffffffff820e9d6a: fsnotify_insert_event.cold (STB_LOCAL)
ffffffff81513770-ffffffff815138e6: fsnotify_insert_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fsnotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *event, int (*merge)(struct fsnotify_group *, struct fsnotify_event *), void (*insert)(struct fsnotify_group *, struct fsnotify_event *));
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
ffffffff821c6804-ffffffff821c681f: fsnotify_insert_event.cold (STB_LOCAL)
ffffffff81547c00-ffffffff81547d76: fsnotify_insert_event (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
