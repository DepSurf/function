# Function: <code>copy_info_to_user</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b410)
Location: fs/notify/fanotify/fanotify_user.c:220
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff8136b410-ffffffff8136b6ee: copy_info_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81378480)
Location: fs/notify/fanotify/fanotify_user.c:228
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff81378480-ffffffff813787a1: copy_info_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f0a0)
Location: fs/notify/fanotify/fanotify_user.c:306
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff8137f0a0-ffffffff8137f3c0: copy_info_to_user (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int info_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>fsid, fh, name, name_len, buf, count</code> ➡️ <code>fsid, fh, info_type, name, name_len, buf, count</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
