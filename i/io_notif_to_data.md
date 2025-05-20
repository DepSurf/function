# Function: <code>io_notif_to_data</code>

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
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff81797cf9)
Location: io_uring/notif.h:24
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/notif.c (ffffffff817a5306)
Location: io_uring/notif.h:24
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
  - io_uring/notif.c:io_notif_set_extended
  - io_uring/notif.c:io_notif_complete_tw_ext
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff817d8a79)
Location: io_uring/notif.h:25
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/notif.c (ffffffff817e62d6)
Location: io_uring/notif.h:25
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
  - io_uring/notif.c:io_notif_set_extended
  - io_uring/notif.c:io_notif_complete_tw_ext
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In io_uring/net.c (ffffffff8181cd89)
Location: io_uring/notif.h:25
Inline: True
Inline callers:
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_sendmsg_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc
  - io_uring/net.c:io_send_zc_prep
  - io_uring/net.c:io_send_zc_cleanup
```
```
In io_uring/notif.c (ffffffff8182a4f6)
Location: io_uring/notif.h:25
Inline: True
Inline callers:
  - io_uring/notif.c:io_alloc_notif
  - io_uring/notif.c:io_notif_set_extended
  - io_uring/notif.c:io_notif_complete_tw_ext
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
