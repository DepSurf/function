# Function: <code>sk_rmem_alloc_get</code>

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
In net/core/sock_diag.c (ffffffff81732fe6)
Location: include/net/sock.h:1869
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff8174abba)
Location: include/net/sock.h:1869
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff817849d5)
Location: include/net/sock.h:1869
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8178736b)
Location: include/net/sock.h:1869
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff817a226b)
Location: include/net/sock.h:1869
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/datagram.c (ffffffff817f5b2c)
Location: include/net/sock.h:1869
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
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
In net/core/sock_diag.c (ffffffff8179ea06)
Location: include/net/sock.h:1839
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff817b77ea)
Location: include/net/sock.h:1839
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff817f1fb3)
Location: include/net/sock.h:1839
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff817f4509)
Location: include/net/sock.h:1839
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff8180ff79)
Location: include/net/sock.h:1839
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81864c0a)
Location: include/net/sock.h:1839
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
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
In net/core/sock_diag.c (ffffffff817cd3d6)
Location: include/net/sock.h:1901
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_put_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff817e728a)
Location: include/net/sock.h:1901
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81822da0)
Location: include/net/sock.h:1901
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818255d6)
Location: include/net/sock.h:1901
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff818414c6)
Location: include/net/sock.h:1901
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/datagram.c (ffffffff818972ea)
Location: include/net/sock.h:1901
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
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
In net/core/sock.c (ffffffff817b643b)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81806f95)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81843980)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81846506)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81862d36)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/datagram.c (ffffffff818bd740)
Location: include/net/sock.h:1926
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
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
In net/core/sock.c (ffffffff8182e9fb)
Location: include/net/sock.h:1940
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81885d45)
Location: include/net/sock.h:1940
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff818c33c0)
Location: include/net/sock.h:1940
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff818c5f36)
Location: include/net/sock.h:1940
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff818e2e66)
Location: include/net/sock.h:1940
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/datagram.c (ffffffff81940860)
Location: include/net/sock.h:1940
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_dgram_sock_seq_show
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
In net/core/sock.c (ffffffff81878e7b)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff818d96fe)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81919030)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8191b245)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819397d6)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81982bb3)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff8198713f)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff819957c1)
Location: include/net/sock.h:1942
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff8189982b)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81905eee)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81947800)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819497c5)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81969466)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff819b91b3)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff819bda5f)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff819cc0a1)
Location: include/net/sock.h:2027
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff818e3e2b)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff8196717c)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff819abe94)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819ade37)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819d00b6)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81a27cc3)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a2c54f)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a3ab81)
Location: include/net/sock.h:2039
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff8191600b)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff8199dc0c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff819e2b44)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819e4b47)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a06c06)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81a5e723)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a6308f)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a71801)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff819e764a)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a76b08)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81ad0105)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ad2798)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
```
```
In net/ipv4/ping.c (ffffffff81af6647)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
```
```
In net/ipv6/udp.c (ffffffff81b575f3)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81b5bb2f)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81b6b101)
Location: include/net/sock.h:2098
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff819e7818)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a7f888)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81adc085)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sock_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ade6d8)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_format_sock
```
```
In net/ipv4/ping.c (ffffffff81b034c7)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_format_sock
```
```
In net/ipv6/udp.c (ffffffff81b65b33)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81b6a36f)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81b79b81)
Location: include/net/sock.h:2117
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff819cd1e9)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81a68851)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81ac6f44)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81ac9617)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81aeed46)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81b53cc3)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81b5869f)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81b686a1)
Location: include/net/sock.h:2134
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff81a7cafd)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/core/sock.c:sock_getsockopt
```
```
In net/netlink/af_netlink.c (ffffffff81b21eae)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81b85764)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81b87e87)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81baf116)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81c1b1e3)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81c1fa2f)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81c30361)
Location: include/net/sock.h:2174
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff81bf25fb)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81caa86c)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81d16330)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81d19047)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81d42444)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81db78e3)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81dbc6af)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81dcd9c1)
Location: include/net/sock.h:2292
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff81d9fe2b)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81e6793c)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81edc500)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81edf797)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81f0b2b4)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81f87713)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81f8c66f)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81f9eb71)
Location: include/net/sock.h:2327
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff81e0e5eb)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81ec371c)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff81f3b64d)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff81f3ed84)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81f6ae91)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81fe7ba3)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81feceef)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81fff631)
Location: include/net/sock.h:2315
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff81ecb07b)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff81f86b3c)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff8200176d)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff820050e4)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff82031541)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff820b5b93)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff820baaef)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff820ce341)
Location: include/net/sock.h:2305
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffff800010baefb0)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffff800010c4b0d8)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffff800010c96a2c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffff800010c991dc)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffff800010cbfb8c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffff800010d237d0)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffff800010d28394)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffff800010d3a228)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (c0cccadc)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (c0d5bc24)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (c0da50fc)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (c0da80d8)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (c0dcb658)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (c0e280cc)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (c0e2ce18)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (c0e3c758)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (c000000000c84cf0)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (c000000000d49334)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (c000000000da8670)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (c000000000dabdbc)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (c000000000ddac3c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (c000000000e53814)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (c000000000e596c4)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (c000000000e6d424)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffe000740ade)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffe0007b83a0)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffe0007f5c8e)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffe0007f7728)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffe0008158fe)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffe000864f66)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffe000869c30)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffe000876ed0)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff818b600b)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff8193da7c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff819829b4)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819849b7)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff819a69a6)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff819fddb3)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a0271f)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a10e91)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff8186ff5b)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff818f757c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff8193c474)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff8193e477)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81960466)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff819bab73)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff819bf4df)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff819cdc51)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff8190700b)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff8198ec0c)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff819ed184)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819ef187)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a11246)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81a68833)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a6d19f)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a7b911)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
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
In net/core/sock.c (ffffffff8192803b)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/sock.c:sk_get_meminfo
```
```
In net/netlink/af_netlink.c (ffffffff819b14cc)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_seq_show
```
```
In net/ipv4/raw.c (ffffffff819f7064)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_seq_show
```
```
In net/ipv4/udp.c (ffffffff819f9977)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_seq_show
```
```
In net/ipv4/ping.c (ffffffff81a1bbb6)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
```
In net/ipv6/udp.c (ffffffff81a74e23)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_seq_show
```
```
In net/ipv6/raw.c (ffffffff81a797bf)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_seq_show
```
```
In net/ipv6/ping.c (ffffffff81a88161)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/ipv6/ping.c:ping_v6_seq_show
```
</details>
</li>
</ul>

## Differences
