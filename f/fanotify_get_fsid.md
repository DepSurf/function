# Function: <code>fanotify_get_fsid</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__kernel_fsid_t fanotify_get_fsid(struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8136a110)
Location: fs/notify/fanotify/fanotify.c:466
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8136a110-ffffffff8136a168: fanotify_get_fsid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__kernel_fsid_t fanotify_get_fsid(struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813773d0)
Location: fs/notify/fanotify/fanotify.c:620
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff813773d0-ffffffff81377428: fanotify_get_fsid (STB_LOCAL)
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:665
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:665
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:838
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:841
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:845
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
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
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:838
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (c0000000004f522c)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffe0002a13ce)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:346
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
