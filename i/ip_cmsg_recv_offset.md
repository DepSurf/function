# Function: <code>ip_cmsg_recv_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sk_buff *skb, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8175f910)
Location: net/ipv4/ip_sockglue.c:154
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff8175f910-ffffffff8175fc6f: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sk_buff *skb, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cbbb0)
Location: net/ipv4/ip_sockglue.c:155
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff817cbbb0-ffffffff817cbf18: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fb830)
Location: net/ipv4/ip_sockglue.c:167
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff817fb830-ffffffff817fbc09: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181bbf0)
Location: net/ipv4/ip_sockglue.c:167
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff8181bbf0-ffffffff8181bfc0: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189ab20)
Location: net/ipv4/ip_sockglue.c:169
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff8189ab20-ffffffff8189aefd: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818eeff0)
Location: net/ipv4/ip_sockglue.c:174
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff818eeff0-ffffffff818ef437: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191c830)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff8191c830-ffffffff8191cc5a: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8197eb90)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff8197eb90-ffffffff8197efba: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b5f90)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff819b5f90-ffffffff819b63ba: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa0800)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81aa0800-ffffffff81aa0c29: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa9c70)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81aa9c70-ffffffff81aaa099: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a94e40)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81a94e40-ffffffff81a9525d: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b502a0)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81b502a0-ffffffff81b506bd: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cde7c0)
Location: net/ipv4/ip_sockglue.c:173
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81cde7c0-ffffffff81cdec56: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9e6e0)
Location: net/ipv4/ip_sockglue.c:173
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81e9e6e0-ffffffff81e9eb76: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efcee0)
Location: net/ipv4/ip_sockglue.c:173
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81efcee0-ffffffff81efd375: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc0e30)
Location: net/ipv4/ip_sockglue.c:169
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81fc0e30-ffffffff81fc12c1: ip_cmsg_recv_offset (STB_GLOBAL)
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
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c65c98)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffff800010c65c98-ffff800010c66010: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c0d75864)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
c0d75864-c0d75c64: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6a440)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
c000000000d6a440-c000000000d6a8f4: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffe0007cd386)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffe0007cd386-ffffffe0007cd6b0: ip_cmsg_recv_offset (STB_GLOBAL)
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
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81955e00)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff81955e00-ffffffff8195622a: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8190f8f0)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff8190f8f0-ffffffff8190fd1a: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c05d0)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff819c05d0-ffffffff819c09fa: ip_cmsg_recv_offset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ip_cmsg_recv_offset(struct msghdr *msg, struct sock *sk, struct sk_buff *skb, int tlen, int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c9fb0)
Location: net/ipv4/ip_sockglue.c:171
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_recv_error
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv4/ping.c:ping_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/datagram.c:ipv6_recv_error
```
**Symbols:**

```
ffffffff819c9fb0-ffffffff819ca3da: ip_cmsg_recv_offset (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *sk</code>
</li>
<li>
<b>Param added. </b>
<code>int tlen</code>
</li>
<li>
<b>Param reordered. </b>
<code>msg, skb, offset</code> ➡️ <code>msg, sk, skb, tlen, offset</code>
</li>
</ul>
</details>
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
