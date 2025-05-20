# Function: <code>import_single_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fdd30)
Location: lib/iov_iter.c:839
Inline: False
Direct callers:
  - fs/aio.c:aio_run_iocb
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
```
**Symbols:**

```
ffffffff813fdd30-ffffffff813fdda2: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814424e0)
Location: lib/iov_iter.c:795
Inline: False
Direct callers:
  - fs/aio.c:aio_run_iocb
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
```
**Symbols:**

```
ffffffff814424e0-ffffffff81442552: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8145f930)
Location: lib/iov_iter.c:1309
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
```
**Symbols:**

```
ffffffff8145f930-ffffffff8145f9a2: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464f70)
Location: lib/iov_iter.c:1433
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
```
**Symbols:**

```
ffffffff81464f70-ffffffff81464fe2: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490ef0)
Location: lib/iov_iter.c:1435
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:SYSC_recvfrom
  - net/socket.c:SYSC_sendto
```
**Symbols:**

```
ffffffff81490ef0-ffffffff81490f62: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c6140)
Location: lib/iov_iter.c:1565
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff814c6140-ffffffff814c61b4: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da8c0)
Location: lib/iov_iter.c:1661
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff814da8c0-ffffffff814da91e: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81506080)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff81506080-ffffffff815060dc: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81524060)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff81524060-ffffffff815240e9: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587c20)
Location: lib/iov_iter.c:1719
Inline: False
Direct callers:
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_import_iovec
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff81587c20-ffffffff81587ca9: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a4c90)
Location: lib/iov_iter.c:1818
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_import_iovec
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff815a4c90-ffffffff815a4d12: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815ab4b0)
Location: lib/iov_iter.c:2106
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_import_iovec
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff815ab4b0-ffffffff815ab511: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81614ad0)
Location: lib/iov_iter.c:1964
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - fs/io_uring.c:io_recv
  - fs/io_uring.c:io_send
  - fs/io_uring.c:io_import_iovec
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81614ad0-ffffffff81614b33: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816e0cc0)
Location: lib/iov_iter.c:2013
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - block/blk-map.c:blk_rq_map_user
  - io_uring/io_uring.c:io_recv
  - io_uring/io_uring.c:io_send
  - io_uring/io_uring.c:__io_import_iovec
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff816e0cc0-ffffffff816e0d39: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff817d11d0)
Location: lib/iov_iter.c:1865
Inline: False
Direct callers:
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_send
  - io_uring/rw.c:__io_import_iovec
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff817d11d0-ffffffff817d124e: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81810280)
Location: lib/iov_iter.c:1524
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_events_write
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - drivers/char/random.c:random_ioctl
  - drivers/char/random.c:__ia32_sys_getrandom
  - drivers/char/random.c:__x64_sys_getrandom
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81810280-ffffffff81810300: import_single_range (STB_GLOBAL)
```
</details>
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
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062dfc8)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffff80001062dfc8-ffff80001062e068: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4008)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
c07d4008-c07d4088: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d05c0)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
c0000000007d05c0-c0000000007d067c: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d378)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffe00045d378-ffffffe00045d3c6: import_single_range (STB_GLOBAL)
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
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151c640)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff8151c640-ffffffff8151c6c9: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c930)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff8150c930-ffffffff8150c9b9: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815186d0)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff815186d0-ffffffff81518759: import_single_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int import_single_range(int rw, void *buf, size_t len, struct iovec *iov, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81531a10)
Location: lib/iov_iter.c:1683
Inline: False
Direct callers:
  - fs/aio.c:aio_setup_rw
  - block/blk-map.c:blk_rq_map_user
  - net/socket.c:__sys_recvfrom
  - net/socket.c:__sys_sendto
```
**Symbols:**

```
ffffffff81531a10-ffffffff81531a99: import_single_range (STB_GLOBAL)
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
