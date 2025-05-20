# Function: <code>__sock_recv_cmsgs</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sock_recv_cmsgs(struct msghdr *msg, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be7970)
Location: net/socket.c:979
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81be7970-ffffffff81be7b0a: __sock_recv_cmsgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sock_recv_cmsgs(struct msghdr *msg, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d93e30)
Location: net/socket.c:984
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81d93e30-ffffffff81d93fb6: __sock_recv_cmsgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sock_recv_cmsgs(struct msghdr *msg, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e019d0)
Location: net/socket.c:1002
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81e019d0-ffffffff81e01b3b: __sock_recv_cmsgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sock_recv_cmsgs(struct msghdr *msg, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebe390)
Location: net/socket.c:1024
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_recvmsg
  - net/ipv4/udp.c:udp_recvmsg
  - net/ipv6/udp.c:udpv6_recvmsg
  - net/ipv6/raw.c:rawv6_recvmsg
  - net/packet/af_packet.c:packet_recvmsg
  - net/mctp/af_mctp.c:mctp_recvmsg
```
**Symbols:**

```
ffffffff81ebe390-ffffffff81ebe4fd: __sock_recv_cmsgs (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
