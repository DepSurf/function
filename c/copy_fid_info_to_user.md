# Function: <code>copy_fid_info_to_user</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_fid_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc050)
Location: fs/notify/fanotify/fanotify_user.c:319
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
```
**Symbols:**

```
ffffffff813cc050-ffffffff813cc370: copy_fid_info_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_fid_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814547b0)
Location: fs/notify/fanotify/fanotify_user.c:373
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
```
**Symbols:**

```
ffffffff814547b0-ffffffff81454b17: copy_fid_info_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_fid_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e36a0)
Location: fs/notify/fanotify/fanotify_user.c:373
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
```
**Symbols:**

```
ffffffff814e36a0-ffffffff814e3a2f: copy_fid_info_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_fid_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81519fe0)
Location: fs/notify/fanotify/fanotify_user.c:413
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
```
**Symbols:**

```
ffffffff81519fe0-ffffffff8151a346: copy_fid_info_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_fid_info_to_user(__kernel_fsid_t *fsid, struct fanotify_fh *fh, int info_type, const char *name, size_t name_len, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154e3b0)
Location: fs/notify/fanotify/fanotify_user.c:412
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
```
**Symbols:**

```
ffffffff8154e3b0-ffffffff8154e716: copy_fid_info_to_user (STB_LOCAL)
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
