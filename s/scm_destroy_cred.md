# Function: <code>scm_destroy_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8170e763)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8174c62d)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff817befbf)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_destruct_scm
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817760b7)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff817b8346)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8182c536)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817a3337)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff817e7e26)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8185dfed)
Location: include/net/scm.h:62
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff817c1440)
Location: include/net/scm.h:63
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81807b49)
Location: include/net/scm.h:63
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff818834f3)
Location: include/net/scm.h:63
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8183ae55)
Location: include/net/scm.h:64
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff818866b9)
Location: include/net/scm.h:64
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81903be5)
Location: include/net/scm.h:64
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818855b2)
Location: include/net/scm.h:64
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff818d9fa1)
Location: include/net/scm.h:64
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8195c1db)
Location: include/net/scm.h:64
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818a5ce2)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81906a9b)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819909ea)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818f105c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81967d3b)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819fc053)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff819fe139)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81922f9c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8199e7db)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a32ce3)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81a34d29)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f6ffe)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81a783fb)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b279fa)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81b29b79)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f6a6e)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81a811f1)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b3632d)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81b384b1)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819dcbdc)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81a6996a)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b23f0a)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81b26151)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81a8ce1c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81b22f27)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81be8556)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81bebdc1)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81c026ba)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81caed51)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81d7f9fd)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81d842c1)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81db1b4a)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81e6c3a1)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81f4d6ed)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81f51b81)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
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
In net/core/scm.c (ffffffff81e21edb)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81ec485c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81fad188)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81fb1555)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
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
In net/core/scm.c (ffffffff81edfe04)
Location: include/net/scm.h:67
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff81f87c24)
Location: include/net/scm.h:67
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8207b5dd)
Location: include/net/scm.h:67
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff8207ec75)
Location: include/net/scm.h:67
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffff800010bbdc8c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffff800010c4d4d4)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffff800010cf26d8)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffff800010cf55f8)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (c0cd9dac)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (c0d5c658)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c0dfa614)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (c0dfc0c0)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (c000000000c970f4)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (c000000000d4a090)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c000000000e18b98)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (c000000000e1b804)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffe00074c02c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffe0007b9270)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffe00083f188)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffe00084109e)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff818c2f9c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8193e64b)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819d2373)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff819d43b9)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8187cedc)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff818f814b)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198f133)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81991179)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81913f9c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff8198f7db)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a3cdf3)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81a3ee39)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff8193512c)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/core/scm.c:__scm_send
```
```
In net/netlink/af_netlink.c (ffffffff819b20bb)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_recvmsg
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a483a6)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
```
In net/unix/scm.c (ffffffff81a4a8f9)
Location: include/net/scm.h:65
Inline: True
Inline callers:
  - net/unix/scm.c:unix_destruct_scm
```
</details>
</li>
</ul>

## Differences
