# Function: <code>sock_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fca70)
Location: net/socket.c:2429
Inline: False
```
**Symbols:**

```
ffffffff816fca70-ffffffff816fcaf2: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763770)
Location: net/socket.c:2431
Inline: False
```
**Symbols:**

```
ffffffff81763770-ffffffff817637f3: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790760)
Location: net/socket.c:2478
Inline: False
```
**Symbols:**

```
ffffffff81790760-ffffffff817907e3: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ad310)
Location: net/socket.c:2528
Inline: False
```
**Symbols:**

```
ffffffff817ad310-ffffffff817ad393: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81825ce0)
Location: net/socket.c:2521
Inline: False
```
**Symbols:**

```
ffffffff81825ce0-ffffffff81825d63: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2642
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818744d5-ffffffff818744f1: sock_register.cold.26 (STB_LOCAL)
ffffffff81871100-ffffffff8187116e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2657
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81894da5-ffffffff81894dc1: sock_register.cold.24 (STB_LOCAL)
ffffffff818915c0-ffffffff8189162e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2868
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818df168-ffffffff818df184: sock_register.cold (STB_LOCAL)
ffffffff818db150-ffffffff818db1be: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81911338-ffffffff81911354: sock_register.cold (STB_LOCAL)
ffffffff8190d2a0-ffffffff8190d30e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2982
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff819e324a-ffffffff819e3266: sock_register.cold (STB_LOCAL)
ffffffff819deee0-ffffffff819def4e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2977
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81c30390-ffffffff81c303ac: sock_register.cold (STB_LOCAL)
ffffffff819de770-ffffffff819de7de: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2961
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81c2266e-ffffffff81c2268a: sock_register.cold (STB_LOCAL)
ffffffff819c54c0-ffffffff819c552e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:3034
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81d34a0b-ffffffff81d34a27: sock_register.cold (STB_LOCAL)
ffffffff81a73b20-ffffffff81a73be0: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:3110
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81f00e8a-ffffffff81f00ea6: sock_register.cold (STB_LOCAL)
ffffffff81be57b0-ffffffff81be5878: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91a10)
Location: net/socket.c:3098
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81d91a10-ffffffff81d91af0: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81dffcf0)
Location: net/socket.c:3136
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81dffcf0-ffffffff81dffdd0: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc190)
Location: net/socket.c:3206
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
  - net/mctp/af_mctp.c:mctp_init
```
**Symbols:**

```
ffffffff81ebc190-ffffffff81ebc270: sock_register (STB_GLOBAL)
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
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba2778)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffff800010ba2778-ffff800010ba2888: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc3114)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c0cc3114-c0cc31c4: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c74df0)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
c000000000c74df0-c000000000c74f00: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a3b4)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffe00073a3b4-ffffffe00073a488: sock_register (STB_GLOBAL)
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
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff818b1338-ffffffff818b1354: sock_register.cold (STB_LOCAL)
ffffffff818ad2a0-ffffffff818ad30e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8186b288-ffffffff8186b2a4: sock_register.cold (STB_LOCAL)
ffffffff818671f0-ffffffff8186725e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff81902338-ffffffff81902354: sock_register.cold (STB_LOCAL)
ffffffff818fe2a0-ffffffff818fe30e: sock_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sock_register(const struct net_proto_family *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/socket.c (0)
Location: net/socket.c:2948
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/ipv4/af_inet.c:inet_init
  - net/unix/af_unix.c:af_unix_init
  - net/ipv6/af_inet6.c:inet6_init
  - net/packet/af_packet.c:packet_init
  - net/xdp/xsk.c:xsk_init
```
**Symbols:**

```
ffffffff8192327c-ffffffff81923298: sock_register.cold (STB_LOCAL)
ffffffff8191d860-ffffffff8191d8cc: sock_register (STB_GLOBAL)
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
