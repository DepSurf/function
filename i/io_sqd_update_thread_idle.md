# Function: <code>io_sqd_update_thread_idle</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138b3c6)
Location: fs/io_uring.c:7040
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_sq_thread_stop
  - fs/io_uring.c:io_sq_thread
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
In fs/io_uring.c (ffffffff81394308)
Location: fs/io_uring.c:6845
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_finish
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
In fs/io_uring.c (ffffffff813e349b)
Location: fs/io_uring.c:7436
Inline: True
Inline callers:
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_finish
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_sqd_update_thread_idle(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e354)
Location: io_uring/io_uring.c:8729
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff81e8e354-ffffffff81e8e3a6: io_sqd_update_thread_idle (STB_LOCAL)
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
In io_uring/sqpoll.c (ffffffff8179ae08)
Location: io_uring/sqpoll.c:77
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
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
In io_uring/sqpoll.c (ffffffff817dbeb7)
Location: io_uring/sqpoll.c:77
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
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
In io_uring/sqpoll.c (ffffffff81820239)
Location: io_uring/sqpoll.c:77
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
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
</ul>
