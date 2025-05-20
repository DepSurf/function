# Function: <code>fanotify_event_object_fh</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8136aace)
Location: fs/notify/fanotify/fanotify.h:111
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136b84e)
Location: fs/notify/fanotify/fanotify.h:111
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_info_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813790ef)
Location: fs/notify/fanotify/fanotify.h:191
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_info_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137fc80)
Location: fs/notify/fanotify/fanotify.h:209
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_info_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cca8a)
Location: fs/notify/fanotify/fanotify.h:209
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_info_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814552ad)
Location: fs/notify/fanotify/fanotify.h:336
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e420d)
Location: fs/notify/fanotify/fanotify.h:336
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151af39)
Location: fs/notify/fanotify/fanotify.h:336
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154f539)
Location: fs/notify/fanotify/fanotify.h:336
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
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
