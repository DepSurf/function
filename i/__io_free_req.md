# Function: <code>__io_free_req</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132dea0)
Location: fs/io_uring.c:610
Inline: False
Direct callers:
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
```
**Symbols:**

```
ffffffff8132dea0-ffffffff8132dee7: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81341400)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff81341400-ffffffff81341472: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81380b80)
Location: fs/io_uring.c:1427
Inline: False
Direct callers:
  - fs/io_uring.c:io_uring_cancel_files
  - fs/io_uring.c:io_cancel_defer_files
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_iopoll_complete
  - fs/io_uring.c:io_put_req
  - fs/io_uring.c:__io_fail_links
```
**Symbols:**

```
ffffffff81380b80-ffffffff81380c9f: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81390270)
Location: fs/io_uring.c:2023
Inline: False
Direct callers:
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
```
**Symbols:**

```
ffffffff81390270-ffffffff81390368: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813950d2)
Location: fs/io_uring.c:1788
Inline: True
Inline callers:
  - fs/io_uring.c:io_free_work
  - fs/io_uring.c:io_put_req_deferred_cb
Direct callers:
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_async_cancel
  - fs/io_uring.c:io_timeout_fn
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_req_complete_failed
```
**Symbols:**

```
ffffffff81393df0-ffffffff81393ec2: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e36e0)
Location: fs/io_uring.c:2028
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_linked_timeout
  - fs/io_uring.c:io_req_task_link_timeout
  - fs/io_uring.c:io_wq_free_work
  - fs/io_uring.c:io_wq_free_work
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_poll_task_func
  - fs/io_uring.c:io_free_req_work
  - fs/io_uring.c:io_free_req_work
```
**Symbols:**

```
ffffffff813e36e0-ffffffff813e3813: __io_free_req (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010401460)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffff800010401460-ffff80001040151c: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d33f8)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
c05d33f8-c05d34b4: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c00000000050b010)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
c00000000050b010-c00000000050b100: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ad776)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffe0002ad776-ffffffe0002ad808: __io_free_req (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813399e0)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff813399e0-ffffffff81339a52: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132a710)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff8132a710-ffffffff8132a782: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813374b0)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff813374b0-ffffffff81337522: __io_free_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __io_free_req(struct io_kiocb *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134a820)
Location: fs/io_uring.c:673
Inline: False
Direct callers:
  - fs/io_uring.c:io_queue_link_head
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_free_req
  - fs/io_uring.c:io_commit_cqring
```
**Symbols:**

```
ffffffff8134a820-ffffffff8134a8ab: __io_free_req (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
