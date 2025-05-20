# Function: <code>io_run_task_work</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81388f62)
Location: fs/io_uring.c:1763
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a2e0)
Location: fs/io_uring.c:2416
Inline: True
Inline callers:
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_iopoll_check
  - fs/io_uring.c:io_iopoll_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool io_run_task_work();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139ee63)
Location: fs/io_uring.c:2255
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
Direct callers:
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff81391c40-ffffffff81391c9b: io_run_task_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool io_run_task_work();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813ef143)
Location: fs/io_uring.c:2467
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:__do_sys_io_uring_enter
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_uring_try_cancel_requests
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
Direct callers:
  - fs/io_uring.c:io_uring_cancel_generic
  - fs/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff813df4b0-ffffffff813df507: io_run_task_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool io_run_task_work();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816d8c30)
Location: io_uring/io_uring.c:2994
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:__do_sys_io_uring_enter
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sq_thread
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_sq_thread
```
**Symbols:**

```
ffffffff816c9310-ffffffff816c937b: io_run_task_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int io_run_task_work();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8178a820)
Location: io_uring/io_uring.h:265
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff8179a210)
Location: io_uring/io_uring.h:265
Inline: True
Direct callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff817a58f0)
Location: io_uring/io_uring.h:265
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_wqe_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8178a820-ffffffff8178a911: io_run_task_work (STB_LOCAL)
ffffffff8179a210-ffffffff8179a301: io_run_task_work (STB_LOCAL)
ffffffff817a58f0-ffffffff817a59e1: io_run_task_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int io_run_task_work();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817cb210)
Location: io_uring/io_uring.h:274
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff817db270)
Location: io_uring/io_uring.h:274
Inline: True
Direct callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff817e68b0)
Location: io_uring/io_uring.h:274
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff817cb210-ffffffff817cb301: io_run_task_work (STB_LOCAL)
ffffffff817db270-ffffffff817db361: io_run_task_work (STB_LOCAL)
ffffffff817e68b0-ffffffff817e69a1: io_run_task_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int io_run_task_work();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180f7b0)
Location: io_uring/io_uring.h:275
Inline: True
Direct callers:
  - io_uring/io_uring.c:io_uring_cancel_generic
  - io_uring/io_uring.c:io_uring_try_cancel_requests
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_run_task_work_sig
  - io_uring/io_uring.c:io_iopoll_check
```
```
In io_uring/sqpoll.c (ffffffff8181f590)
Location: io_uring/io_uring.h:275
Inline: True
Direct callers:
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
```
```
In io_uring/io-wq.c (ffffffff8182c670)
Location: io_uring/io_uring.h:275
Inline: True
Direct callers:
  - io_uring/io-wq.c:io_wq_worker
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
  - io_uring/io-wq.c:io_worker_handle_work
```
**Symbols:**

```
ffffffff8180f7b0-ffffffff8180f8a6: io_run_task_work (STB_LOCAL)
ffffffff8181f590-ffffffff8181f686: io_run_task_work (STB_LOCAL)
ffffffff8182c670-ffffffff8182c766: io_run_task_work (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
