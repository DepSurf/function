# Function: <code>fanotify_info_file_fh</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81377b0c)
Location: fs/notify/fanotify/fanotify.h:101
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813790fb)
Location: fs/notify/fanotify/fanotify.h:101
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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137e59b)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137fc8c)
Location: fs/notify/fanotify/fanotify.h:102
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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813cb678)
Location: fs/notify/fanotify/fanotify.h:102
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cca8f)
Location: fs/notify/fanotify/fanotify.h:102
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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814533cb)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8145549a)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
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
In fs/notify/fanotify/fanotify.c (ffffffff814e227f)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e43fa)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
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
In fs/notify/fanotify/fanotify.c (ffffffff81518b5a)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b145)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:fanotify_event_len
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
In fs/notify/fanotify/fanotify.c (ffffffff8154cf3a)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154f745)
Location: fs/notify/fanotify/fanotify.h:146
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
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
