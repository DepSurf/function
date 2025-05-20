# Function: <code>proto_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81701a00)
Location: net/core/sock.c:2837
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff81701a00-ffffffff81701c0d: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81768ca0)
Location: net/core/sock.c:2905
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff81768ca0-ffffffff81768ead: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81795bb0)
Location: net/core/sock.c:2927
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff81795bb0-ffffffff81795dbd: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b3e10)
Location: net/core/sock.c:3109
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff817b3e10-ffffffff817b401d: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182c050)
Location: net/core/sock.c:3148
Inline: False
Direct callers:
  - net/ipv4/udplite.c:udplite4_register
```
**Symbols:**

```
ffffffff8182c050-ffffffff8182c258: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3257
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81879887-ffffffff818798c5: proto_register.cold.65 (STB_LOCAL)
ffffffff818761c0-ffffffff818763b1: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3208
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8189a4d7-ffffffff8189a515: proto_register.cold.64 (STB_LOCAL)
ffffffff81896a40-ffffffff81896c31: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3358
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818e4b44-ffffffff818e4bc5: proto_register.cold (STB_LOCAL)
ffffffff818e0cd0-ffffffff818e0f0d: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81916d07-ffffffff81916d88: proto_register.cold (STB_LOCAL)
ffffffff81912e90-ffffffff819130cd: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3512
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff819e967c-ffffffff819e96fd: proto_register.cold (STB_LOCAL)
ffffffff819e57f0-ffffffff819e5a4a: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3464
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81c303c4-ffffffff81c30445: proto_register.cold (STB_LOCAL)
ffffffff819e5070-ffffffff819e52ca: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3513
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81c226a2-ffffffff81c2271d: proto_register.cold (STB_LOCAL)
ffffffff819cab60-ffffffff819cad96: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3639
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
```
**Symbols:**

```
ffffffff81d34ad3-ffffffff81d34b4e: proto_register.cold (STB_LOCAL)
ffffffff81a7a190-ffffffff81a7a3c6: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3795
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81f00fb8-ffffffff81f01045: proto_register.cold (STB_LOCAL)
ffffffff81becf40-ffffffff81bed1b3: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d99670)
Location: net/core/sock.c:3886
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81d99670-ffffffff81d99983: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e07990)
Location: net/core/sock.c:3917
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81e07990-ffffffff81e07ca9: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec43d0)
Location: net/core/sock.c:3925
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mptcp/protocol.c:mptcp_proto_v6_init
  - net/mptcp/protocol.c:mptcp_proto_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81ec43d0-ffffffff81ec46e9: proto_register (STB_GLOBAL)
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
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bac3e0)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffff800010bac3e0-ffff800010bac668: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9114)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c0cc9114-c0cc9384: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c80b60)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c000000000c80b60-c000000000c80ec8: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073df02)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffe00073df02-ffffffe00073e1aa: proto_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818b6d07-ffffffff818b6d88: proto_register.cold (STB_LOCAL)
ffffffff818b2e90-ffffffff818b30cd: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81870c57-ffffffff81870cd8: proto_register.cold (STB_LOCAL)
ffffffff8186cde0-ffffffff8186d01d: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81907d07-ffffffff81907d88: proto_register.cold (STB_LOCAL)
ffffffff81903e90-ffffffff819040cd: proto_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int proto_register(struct proto *prot, int alloc_slab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:3373
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/udplite.c:udplite4_register
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81928d38-ffffffff81928db9: proto_register.cold (STB_LOCAL)
ffffffff81924f10-ffffffff8192514d: proto_register (STB_GLOBAL)
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
