# Function: <code>io_clean_op</code>

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
In fs/io_uring.c (ffffffff813901e5)
Location: fs/io_uring.c:1050
Inline: True
Inline callers:
  - fs/io_uring.c:io_dismantle_req
  - fs/io_uring.c:__io_cqring_fill_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_clean_op(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390450)
Location: fs/io_uring.c:6069
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_dismantle_req
```
**Symbols:**

```
ffffffff81390450-ffffffff813905f2: io_clean_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_clean_op(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e16c0)
Location: fs/io_uring.c:6618
Inline: False
Direct callers:
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_connect
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_recvmsg
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_sendmsg
  - fs/io_uring.c:io_close
  - fs/io_uring.c:io_provide_buffers
  - fs/io_uring.c:io_openat2
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_req_task_complete
  - fs/io_uring.c:io_dismantle_req
```
**Symbols:**

```
ffffffff813e16c0-ffffffff813e18ae: io_clean_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void io_clean_op(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cf080)
Location: io_uring/io_uring.c:7923
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_put
```
**Symbols:**

```
ffffffff816cf080-ffffffff816cf2f0: io_clean_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_clean_op(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178b5d0)
Location: io_uring/io_uring.c:1796
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:io_free_req
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff8178b5d0-ffffffff8178b780: io_clean_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_clean_op(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cc8a0)
Location: io_uring/io_uring.c:367
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff817cc8a0-ffffffff817cca45: io_clean_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void io_clean_op(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180fb90)
Location: io_uring/io_uring.c:381
Inline: False
Direct callers:
  - io_uring/io_uring.c:io_free_batch_list
  - io_uring/io_uring.c:__io_req_complete_post
```
**Symbols:**

```
ffffffff8180fb90-ffffffff8180fd37: io_clean_op (STB_LOCAL)
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
