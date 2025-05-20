# Function: <code>revert_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a2160)
Location: kernel/cred.c:549
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810a2160-ffffffff810a2190: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5910)
Location: kernel/cred.c:549
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/namei.c:follow_managed
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810a5910-ffffffff810a5940: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab570)
Location: kernel/cred.c:549
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810ab570-ffffffff810ab5a0: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a8130)
Location: kernel/cred.c:550
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810a8130-ffffffff810a8161: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ae8b0)
Location: kernel/cred.c:550
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810ae8b0-ffffffff810ae8e1: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b5630)
Location: kernel/cred.c:550
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810b5630-ffffffff810b5661: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be880)
Location: kernel/cred.c:552
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810be880-ffffffff810be8b6: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c48b0)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810c48b0-ffffffff810c48e5: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cd9c0)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810cd9c0-ffffffff810cd9f5: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d7650)
Location: kernel/cred.c:585
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io-wq.c:__io_worker_unuse
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810d7650-ffffffff810d7685: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d2450)
Location: kernel/cred.c:585
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:__io_queue_sqe
  - fs/io_uring.c:__io_queue_sqe
  - fs/io-wq.c:__io_worker_unuse
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810d2450-ffffffff810d2485: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d4030)
Location: kernel/cred.c:597
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810d4030-ffffffff810d4065: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e71b0)
Location: kernel/cred.c:595
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810e71b0-ffffffff810e71e5: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101420)
Location: kernel/cred.c:595
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_issue_sqe
  - drivers/base/firmware_loader/main.c:_request_firmware
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81101420-ffffffff81101469: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811265b0)
Location: kernel/cred.c:595
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/sqpoll.c:io_sq_thread
  - drivers/base/firmware_loader/main.c:_request_firmware
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff811265b0-ffffffff811265f9: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133a60)
Location: kernel/cred.c:595
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/coredump.c:do_coredump
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/sqpoll.c:io_sq_thread
  - drivers/base/firmware_loader/main.c:_request_firmware
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff81133a60-ffffffff81133aa9: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113e9d0)
Location: kernel/cred.c:517
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/trace/trace_events_user.c:user_event_set_call_visible
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/backing-file.c:backing_file_mmap
  - fs/backing-file.c:backing_file_splice_read
  - fs/coredump.c:do_coredump
  - io_uring/io_uring.c:io_issue_sqe
  - io_uring/sqpoll.c:io_sq_thread
  - drivers/base/firmware_loader/main.c:_request_firmware
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff8113e9d0-ffffffff8113ea1b: revert_creds (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cdc0)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffff80001012cdc0-ffff80001012ce30: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037cfd8)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c037cfd8-c037d048: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175d00)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
c000000000175d00-c000000000175d54: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e1354)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffe0000e1354-ffffffe0000e13a2: revert_creds (STB_GLOBAL)
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
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7d40)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810c7d40-ffffffff810c7d75: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b6560)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810b6560-ffffffff810b6595: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7290)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810c7290-ffffffff810c72c5: revert_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void revert_creds(const struct cred *old);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cf760)
Location: kernel/cred.c:582
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_wq_submit_work
  - fs/io_uring.c:io_poll_complete_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810cf760-ffffffff810cf795: revert_creds (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
