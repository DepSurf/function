# Function: <code>rps_record_sock_flow</code>

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
In drivers/net/tun.c (ffffffff815ef3e9)
Location: include/linux/netdevice.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff81766265)
Location: include/linux/netdevice.h:668
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81788aa7)
Location: include/linux/netdevice.h:668
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff817938ef)
Location: include/linux/netdevice.h:668
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_accept
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_sendpage
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
In drivers/net/tun.c (ffffffff8164df20)
Location: include/linux/netdevice.h:670
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff817d27c5)
Location: include/linux/netdevice.h:670
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff817f6407)
Location: include/linux/netdevice.h:670
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff8180270b)
Location: include/linux/netdevice.h:670
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8167fc1b)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff81802d6f)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81826ed8)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818336e0)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff81694f88)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff81822b62)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff8184865b)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff81854440)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff816ff6cc)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff818a1c83)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff818c80bb)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/ipv4/af_inet.c (ffffffff818d42d6)
Location: include/linux/netdevice.h:660
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8173f2bc)
Location: include/linux/netdevice.h:671
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/ipv4/tcp.c (ffffffff818f679a)
Location: include/linux/netdevice.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8192a9f1)
Location: include/linux/netdevice.h:671
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8175f326)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81926682)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8195a1f1)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_sendpage
  - net/ipv4/af_inet.c:inet_sendmsg
  - net/ipv4/af_inet.c:inet_accept
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
In drivers/net/tun.c (ffffffff8179cb62)
Location: include/linux/netdevice.h:712
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81989015)
Location: include/linux/netdevice.h:712
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819bedc3)
Location: include/linux/netdevice.h:712
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819fe5b3)
Location: include/linux/netdevice.h:712
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817c05f4)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819c0475)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819f5a03)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a351a3)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8188c136)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81aa9abc)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ae3f63)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b2a143)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8189a219)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81ab6e45)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81af0e78)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b38a88)
Location: include/linux/netdevice.h:721
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8187bfe9)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81aa2045)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81adc638)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81b26778)
Location: include/linux/netdevice.h:714
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff8190d526)
Location: include/linux/netdevice.h:707
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81b5de15)
Location: include/linux/netdevice.h:707
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81b9ba25)
Location: include/linux/netdevice.h:707
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81bec1d5)
Location: include/linux/netdevice.h:707
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81a60622)
Location: include/linux/netdevice.h:735
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81cec848)
Location: include/linux/netdevice.h:735
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81d2dd22)
Location: include/linux/netdevice.h:735
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81d84722)
Location: include/linux/netdevice.h:735
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81bebd12)
Location: include/linux/netdevice.h:749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81eb071a)
Location: include/linux/netdevice.h:749
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81ef5c42)
Location: include/linux/netdevice.h:749
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81f52042)
Location: include/linux/netdevice.h:749
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81c441c2)
Location: include/linux/netdevice.h:761
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81f0ebe9)
Location: include/linux/netdevice.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81f54fe2)
Location: include/linux/netdevice.h:761
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81fb1a52)
Location: include/linux/netdevice.h:761
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81cf9a82)
Location: include/linux/netdevice.h:790
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81fd2d4e)
Location: include/linux/netdevice.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8201b252)
Location: include/linux/netdevice.h:790
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_send_prepare
  - net/ipv4/af_inet.c:__inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff8207f172)
Location: include/linux/netdevice.h:790
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffff8000109de014)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffff800010c72a08)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffff800010cac74c)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffff800010cf586c)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (c0ac1a28)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (c0d7f9ac)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c0db832c)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (c0dfc2b4)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (c000000000a9cffc)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (c000000000d7791c)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (c000000000dc1cfc)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (c000000000e1ba5c)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffe000625ae8)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffe0007d6248)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffe0008061c6)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffe000841232)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817850c4)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819602e5)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff819957a3)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819d4833)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff81764a14)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff81919dd5)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff8194f263)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff819915f3)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817b5474)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819caab5)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81a00043)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a3f2b3)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
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
In drivers/net/tun.c (ffffffff817cf672)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In net/ipv4/tcp.c (ffffffff819d462e)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
```
In net/ipv4/af_inet.c (ffffffff81a0a600)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_recvmsg
  - net/ipv4/af_inet.c:inet_accept
```
```
In net/ipv6/af_inet6.c (ffffffff81a4ad90)
Location: include/linux/netdevice.h:716
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_recvmsg
```
</details>
</li>
</ul>

## Differences
