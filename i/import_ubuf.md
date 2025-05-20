# Function: <code>import_ubuf</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int import_ubuf(int rw, void *buf, size_t len, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff818157b0)
Location: lib/iov_iter.c:1537
Inline: False
Direct callers:
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_send
  - io_uring/rw.c:__io_import_iovec
  - lib/iov_iter.c:__import_iovec
```
**Symbols:**

```
ffffffff818157b0-ffffffff8181582f: import_ubuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int import_ubuf(int rw, void *buf, size_t len, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81855d70)
Location: lib/iov_iter.c:1349
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:user_events_write
  - fs/aio.c:aio_write
  - fs/aio.c:aio_read
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_recv
  - io_uring/net.c:io_send
  - io_uring/rw.c:__io_import_iovec
  - lib/iov_iter.c:__import_iovec
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
ffffffff81855d70-ffffffff81855de8: import_ubuf (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
