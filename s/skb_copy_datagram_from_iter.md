# Function: <code>skb_copy_datagram_from_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8170d350)
Location: net/core/datagram.c:443
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff8170d350-ffffffff8170d54b: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817749a0)
Location: net/core/datagram.c:465
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff817749a0-ffffffff81774b99: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817a1ca0)
Location: net/core/datagram.c:485
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff817a1ca0-ffffffff817a1e99: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff817c02d0)
Location: net/core/datagram.c:510
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff817c02d0-ffffffff817c04b4: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81839cf0)
Location: net/core/datagram.c:511
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81839cf0-ffffffff81839ed4: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81884430)
Location: net/core/datagram.c:509
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81884430-ffffffff81884606: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818a4190)
Location: net/core/datagram.c:544
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff818a4190-ffffffff818a435d: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/datagram.c (0)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff818f04c3-ffffffff818f0510: skb_copy_datagram_from_iter.cold (STB_LOCAL)
ffffffff818ef7d0-ffffffff818ef9a3: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819217d0)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819217d0-ffffffff819219c4: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4c10)
Location: net/core/datagram.c:547
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819f4c10-ffffffff819f4e02: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819f4540)
Location: net/core/datagram.c:547
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819f4540-ffffffff819f4732: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819da6f0)
Location: net/core/datagram.c:547
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819da6f0-ffffffff819da8e0: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81a8ac20)
Location: net/core/datagram.c:547
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81a8ac20-ffffffff81a8ae10: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81c00270)
Location: net/core/datagram.c:544
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81c00270-ffffffff81c00465: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81daf690)
Location: net/core/datagram.c:541
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81daf690-ffffffff81daf885: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81e1f8d0)
Location: net/core/datagram.c:541
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81e1f8d0-ffffffff81e1fafe: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81edcf80)
Location: net/core/datagram.c:560
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:queue_oob
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81edcf80-ffffffff81edd1ae: skb_copy_datagram_from_iter (STB_GLOBAL)
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
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffff800010bbbe58)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffff800010bbbe58-ffff800010bbc050: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c0cd8294)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
c0cd8294-c0cd84d0: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (c000000000c94ea0)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
c000000000c94ea0-c000000000c951d8: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffe00074ac5c)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffe00074ac5c-ffffffe00074ae08: skb_copy_datagram_from_iter (STB_GLOBAL)
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
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff818c17d0)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff818c17d0-ffffffff818c19c4: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff8187b710)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff8187b710-ffffffff8187b904: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff819127d0)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff819127d0-ffffffff819129c4: skb_copy_datagram_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_copy_datagram_from_iter(struct sk_buff *skb, int offset, struct iov_iter *from, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/datagram.c (ffffffff81933950)
Location: net/core/datagram.c:543
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/datagram.c:zerocopy_sg_from_iter
  - net/core/datagram.c:skb_copy_datagram_from_iter
  - net/ipv4/tcp_input.c:tcp_send_rcvq
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/packet/af_packet.c:packet_snd
```
**Symbols:**

```
ffffffff81933950-ffffffff81933b44: skb_copy_datagram_from_iter (STB_GLOBAL)
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
