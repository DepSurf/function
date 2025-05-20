# Function: <code>eventfd_signal_allowed</code>

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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d9c07)
Location: include/linux/eventfd.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
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
In fs/aio.c (ffffffff8146408d)
Location: include/linux/eventfd.h:47
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
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
In fs/aio.c (ffffffff814f439d)
Location: include/linux/eventfd.h:48
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In io_uring/io_uring.c (ffffffff817888c2)
Location: include/linux/eventfd.h:48
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
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
In fs/aio.c (ffffffff8152b16b)
Location: include/linux/eventfd.h:44
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In io_uring/io_uring.c (ffffffff817c8fa2)
Location: include/linux/eventfd.h:44
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
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
In fs/aio.c (ffffffff8156003b)
Location: include/linux/eventfd.h:43
Inline: True
Inline callers:
  - fs/aio.c:aio_poll_wake
```
```
In io_uring/io_uring.c (ffffffff8180dbdf)
Location: include/linux/eventfd.h:43
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_eventfd_signal
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
