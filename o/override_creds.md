# Function: <code>override_creds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a1ea0)
Location: kernel/cred.c:520
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810a1ea0-ffffffff810a1ec5: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a5650)
Location: kernel/cred.c:520
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
ffffffff810a5650-ffffffff810a5675: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ab2b0)
Location: kernel/cred.c:520
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810ab2b0-ffffffff810ab2d5: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810a7e70)
Location: kernel/cred.c:521
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810a7e70-ffffffff810a7e95: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810ae5f0)
Location: kernel/cred.c:521
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:SyS_access
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810ae5f0-ffffffff810ae615: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b5460)
Location: kernel/cred.c:521
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810b5460-ffffffff810b5485: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810be5b0)
Location: kernel/cred.c:523
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810be5b0-ffffffff810be5e3: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c45d0)
Location: kernel/cred.c:541
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810c45d0-ffffffff810c45f8: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cd6e0)
Location: kernel/cred.c:541
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
ffffffff810cd6e0-ffffffff810cd708: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d7380)
Location: kernel/cred.c:544
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:access_override_creds
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:__io_queue_sqe
  - fs/io-wq.c:io_worker_handle_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810d7380-ffffffff810d73a8: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d2140)
Location: kernel/cred.c:544
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:access_override_creds
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:__io_queue_sqe
  - fs/io-wq.c:io_impersonate_work
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810d2140-ffffffff810d2168: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d3d20)
Location: kernel/cred.c:556
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810d3d20-ffffffff810d3d48: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e6ea0)
Location: kernel/cred.c:554
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - fs/open.c:do_faccessat
  - fs/aio.c:aio_fsync_work
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_issue_sqe
  - fs/coredump.c:do_coredump
  - net/dns_resolver/dns_query.c:dns_query
```
**Symbols:**

```
ffffffff810e6ea0-ffffffff810e6ec8: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101050)
Location: kernel/cred.c:554
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
ffffffff81101050-ffffffff81101080: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126140)
Location: kernel/cred.c:554
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
ffffffff81126140-ffffffff81126170: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff811335f0)
Location: kernel/cred.c:554
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
ffffffff811335f0-ffffffff81133620: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113e550)
Location: kernel/cred.c:486
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
ffffffff8113e550-ffffffff8113e582: override_creds (STB_GLOBAL)
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
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffff80001012cea8)
Location: kernel/cred.c:541
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
ffff80001012cea8-ffff80001012cf0c: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c037cb6c)
Location: kernel/cred.c:541
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
c037cb6c-c037cbcc: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (c000000000175800)
Location: kernel/cred.c:541
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
c000000000175800-c000000000175830: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffe0000e11d6)
Location: kernel/cred.c:541
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
ffffffe0000e11d6-ffffffe0000e1208: override_creds (STB_GLOBAL)
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
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c7a60)
Location: kernel/cred.c:541
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
ffffffff810c7a60-ffffffff810c7a88: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810b6280)
Location: kernel/cred.c:541
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
ffffffff810b6280-ffffffff810b62a8: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810c6fb0)
Location: kernel/cred.c:541
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
ffffffff810c6fb0-ffffffff810c6fd8: override_creds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct cred *override_creds(const struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810cf470)
Location: kernel/cred.c:541
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
ffffffff810cf470-ffffffff810cf498: override_creds (STB_GLOBAL)
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
