# Function: <code>io_poll_remove_double</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_poll_remove_double(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137f8e0)
Location: fs/io_uring.c:4240
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_add
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
```
**Symbols:**

```
ffffffff8137f8e0-ffffffff8137f980: io_poll_remove_double (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_poll_remove_double(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138d620)
Location: fs/io_uring.c:5215
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff8138d620-ffffffff8138d6c0: io_poll_remove_double (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_poll_remove_double(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81397430)
Location: fs/io_uring.c:4913
Inline: False
Direct callers:
  - fs/io_uring.c:io_poll_remove_waitqs
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff81397430-ffffffff813974ca: io_poll_remove_double (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_poll_remove_double(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e4510)
Location: fs/io_uring.c:5368
Inline: False
Direct callers:
  - fs/io_uring.c:__io_arm_poll_handler
  - fs/io_uring.c:io_async_task_func
  - fs/io_uring.c:io_poll_task_func
```
**Symbols:**

```
ffffffff813e4510-ffffffff813e45bb: io_poll_remove_double (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
