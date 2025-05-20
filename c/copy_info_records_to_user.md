# Function: <code>copy_info_records_to_user</code>

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
int copy_info_records_to_user(struct fanotify_event *event, struct fanotify_info *info, unsigned int info_mode, int pidfd, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc8b0)
Location: fs/notify/fanotify/fanotify_user.c:435
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff813cc8b0-ffffffff813ccb3d: copy_info_records_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_info_records_to_user(struct fanotify_event *event, struct fanotify_info *info, unsigned int info_mode, int pidfd, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814550b0)
Location: fs/notify/fanotify/fanotify_user.c:493
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff814550b0-ffffffff814554fb: copy_info_records_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_info_records_to_user(struct fanotify_event *event, struct fanotify_info *info, unsigned int info_mode, int pidfd, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e4010)
Location: fs/notify/fanotify/fanotify_user.c:493
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff814e4010-ffffffff814e445b: copy_info_records_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_info_records_to_user(struct fanotify_event *event, struct fanotify_info *info, unsigned int info_mode, int pidfd, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151ad00)
Location: fs/notify/fanotify/fanotify_user.c:533
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff8151ad00-ffffffff8151b181: copy_info_records_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_info_records_to_user(struct fanotify_event *event, struct fanotify_info *info, unsigned int info_mode, int pidfd, char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154f300)
Location: fs/notify/fanotify/fanotify_user.c:532
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
```
**Symbols:**

```
ffffffff8154f300-ffffffff8154f781: copy_info_records_to_user (STB_LOCAL)
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
