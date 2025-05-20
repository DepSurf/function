# Function: <code>io_sq_thread_park</code>

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
In fs/io_uring.c (ffffffff813973e4)
Location: fs/io_uring.c:7482
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_task_requests
  - fs/io_uring.c:io_uring_cancel_task_requests
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_stop
  - fs/io_uring.c:io_sq_thread_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_sq_thread_park(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391bf0)
Location: fs/io_uring.c:7272
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff81391bf0-ffffffff81391c36: io_sq_thread_park (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_sq_thread_park(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813df510)
Location: fs/io_uring.c:7973
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff813df510-ffffffff813df556: io_sq_thread_park (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_sq_thread_park(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e790)
Location: io_uring/io_uring.c:9323
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff81e8e790-ffffffff81e8e7d9: io_sq_thread_park (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_sq_thread_park(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8179a9a0)
Location: io_uring/sqpoll.c:42
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff8179a9a0-ffffffff8179a9ee: io_sq_thread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_sq_thread_park(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff817dba50)
Location: io_uring/sqpoll.c:42
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff817dba50-ffffffff817dba9e: io_sq_thread_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_sq_thread_park(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8181fdd0)
Location: io_uring/sqpoll.c:42
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff8181fdd0-ffffffff8181fe1e: io_sq_thread_park (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
