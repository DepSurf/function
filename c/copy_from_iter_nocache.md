# Function: <code>copy_from_iter_nocache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fbb80)
Location: lib/iov_iter.c:428
Inline: False
Direct callers:
  - fs/dax.c:dax_do_io
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff813fbb80-ffffffff813fbdfa: copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81443860)
Location: lib/iov_iter.c:389
Inline: False
Direct callers:
  - fs/dax.c:dax_do_io
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81443860-ffffffff81443b8a: copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t copy_from_iter_nocache(void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81461910)
Location: lib/iov_iter.c:599
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_actor
```
**Symbols:**

```
ffffffff81461910-ffffffff81461c69: copy_from_iter_nocache (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cfc01)
Location: include/linux/uio.h:128
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e7091)
Location: include/linux/uio.h:166
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81936a2d)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81968ed5)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3c872)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
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
In net/core/skmsg.c (ffffffff81a3ef42)
Location: include/linux/uio.h:159
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4d352)
Location: include/linux/uio.h:167
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
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
In net/core/skmsg.c (ffffffff81b055cf)
Location: include/linux/uio.h:176
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp.c (ffffffff81b5a179)
Location: include/linux/uio.h:176
Inline: True
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
In net/core/skmsg.c (ffffffff81c8ab70)
Location: include/linux/uio.h:185
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp.c (ffffffff81ce84b9)
Location: include/linux/uio.h:185
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
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
In net/core/skmsg.c (ffffffff81e45c50)
Location: include/linux/uio.h:202
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp.c (ffffffff81eabe09)
Location: include/linux/uio.h:202
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
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
In kernel/trace/trace_events_user.c (ffffffff812c3b38)
Location: include/linux/uio.h:217
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In net/core/skmsg.c (ffffffff81ea1260)
Location: include/linux/uio.h:217
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp.c (ffffffff81f0a5c9)
Location: include/linux/uio.h:217
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
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
In kernel/trace/trace_events_user.c (ffffffff812e0388)
Location: include/linux/uio.h:219
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_perf
  - kernel/trace/trace_events_user.c:user_event_ftrace
```
```
In net/core/skmsg.c (ffffffff81f63a60)
Location: include/linux/uio.h:219
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
```
In net/ipv4/tcp.c (ffffffff81fce5c9)
Location: include/linux/uio.h:219
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/mptcp/protocol.c (ffffffff8214cb6f)
Location: include/linux/uio.h:219
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0f594)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d26d2c)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfaed8)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078c0a2)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81908ea5)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c2cb5)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81959ed5)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197c0f5)
Location: include/linux/uio.h:160
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_memcopy_from_iter
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
</ul>
