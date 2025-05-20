# Function: <code>fanotify_info_name</code>

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
In fs/notify/fanotify/fanotify.c (ffffffff81377ac6)
Location: fs/notify/fanotify/fanotify.h:106
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81378ff4)
Location: fs/notify/fanotify/fanotify.h:106
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff8137e54d)
Location: fs/notify/fanotify/fanotify.h:107
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137fbe2)
Location: fs/notify/fanotify/fanotify.h:107
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_event_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff813cb62a)
Location: fs/notify/fanotify/fanotify.h:107
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc960)
Location: fs/notify/fanotify/fanotify.h:107
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff814532b2)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff814e2153)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_copy_name
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff81518a4c)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_copy_name
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
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
In fs/notify/fanotify/fanotify.c (ffffffff8154ce2c)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_copy_name
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: fs/notify/fanotify/fanotify.h:151
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:copy_info_records_to_user
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
