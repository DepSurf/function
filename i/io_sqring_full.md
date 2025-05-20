# Function: <code>io_sqring_full</code>

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
In fs/io_uring.c (ffffffff8138aa14)
Location: fs/io_uring.c:1691
Inline: True
Inline callers:
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:io_sqpoll_wait_sq
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:__io_sq_thread
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
In fs/io_uring.c (ffffffff813a18e6)
Location: fs/io_uring.c:1379
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_sq_thread
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
In fs/io_uring.c (ffffffff813f02f2)
Location: fs/io_uring.c:1594
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_poll
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
In io_uring/io_uring.c (ffffffff816d6df4)
Location: io_uring/io_uring.c:1970
Inline: True
Inline callers:
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_uring_poll
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
In io_uring/io_uring.c (ffffffff81786302)
Location: io_uring/io_uring.h:250
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In io_uring/sqpoll.c (ffffffff8179ac4e)
Location: io_uring/io_uring.h:250
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
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
In io_uring/io_uring.c (ffffffff817c9186)
Location: io_uring/io_uring.h:257
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In io_uring/sqpoll.c (ffffffff817dbcfe)
Location: io_uring/io_uring.h:257
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
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
In io_uring/io_uring.c (ffffffff81816f86)
Location: io_uring/io_uring.h:258
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_uring_poll
```
```
In io_uring/sqpoll.c (ffffffff8182007e)
Location: io_uring/io_uring.h:258
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
  - io_uring/sqpoll.c:io_sqpoll_wait_sq
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
