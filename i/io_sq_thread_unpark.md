# Function: <code>io_sq_thread_unpark</code>

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
In fs/io_uring.c (ffffffff81397435)
Location: fs/io_uring.c:7473
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_cancel_task_requests
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_uring_poll
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_sq_thread_unpark(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391d00)
Location: fs/io_uring.c:7257
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff81391d00-ffffffff81391d40: io_sq_thread_unpark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_sq_thread_unpark(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813df560)
Location: fs/io_uring.c:7958
Inline: False
Direct callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_offload_create
  - fs/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff813df560-ffffffff813df5a0: io_sq_thread_unpark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_sq_thread_unpark(struct io_sq_data *sqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e8e48a)
Location: io_uring/io_uring.c:9308
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_offload_create
  - io_uring/io_uring.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff81e8e48a-ffffffff81e8e4cd: io_sq_thread_unpark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_sq_thread_unpark(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8179a940)
Location: io_uring/sqpoll.c:27
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff8179a940-ffffffff8179a988: io_sq_thread_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_sq_thread_unpark(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff817db9f0)
Location: io_uring/sqpoll.c:27
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff817db9f0-ffffffff817dba38: io_sq_thread_unpark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_sq_thread_unpark(struct io_sq_data *sqd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/sqpoll.c (ffffffff8181fd70)
Location: io_uring/sqpoll.c:27
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/sqpoll.c:io_sqpoll_wq_cpu_affinity
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_offload_create
  - io_uring/sqpoll.c:io_sq_thread_finish
```
**Symbols:**

```
ffffffff8181fd70-ffffffff8181fdb8: io_sq_thread_unpark (STB_GLOBAL)
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
