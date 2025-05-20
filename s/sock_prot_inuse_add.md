# Function: <code>sock_prot_inuse_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81700730)
Location: net/core/sock.c:2711
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_create
  - net/netlink/af_netlink.c:netlink_release
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81700730-ffffffff8170074c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81767120)
Location: net/core/sock.c:2779
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81767120-ffffffff8176713c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817941a0)
Location: net/core/sock.c:2801
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff817941a0-ffffffff817941bc: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b2560)
Location: net/core/sock.c:2983
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff817b2560-ffffffff817b257c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182a710)
Location: net/core/sock.c:3043
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff8182a710-ffffffff8182a72c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874870)
Location: net/core/sock.c:3118
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81874870-ffffffff8187488c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81895130)
Location: net/core/sock.c:3069
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81895130-ffffffff8189514c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df5f0)
Location: net/core/sock.c:3217
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff818df5f0-ffffffff818df610: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819117c0)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff819117c0-ffffffff819117e0: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e35f0)
Location: net/core/sock.c:3361
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff819e35f0-ffffffff819e3610: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3140)
Location: net/core/sock.c:3313
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff819e3140-ffffffff819e3160: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9160)
Location: net/core/sock.c:3336
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff819c9160-ffffffff819c9180: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a78500)
Location: net/core/sock.c:3462
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a78500-ffffffff81a78520: sock_prot_inuse_add (STB_GLOBAL)
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
In net/netlink/af_netlink.c (ffffffff81cae324)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce2600)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce33d4)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81d15a22)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81d1b47a)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81d42b2f)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81d7ef97)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81db25e4)
Location: include/net/sock.h:1479
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def6e0)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81df34e5)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e17aec)
Location: include/net/sock.h:1479
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In net/netlink/af_netlink.c (ffffffff81e6b7a3)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3681)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5d3b)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81edbdd2)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81ee0235)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f0b9ff)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81f4c2f3)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81f810fd)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc37b0)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81fc82a5)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81feea9c)
Location: include/net/sock.h:1537
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
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
In net/netlink/af_netlink.c (ffffffff81ec77e3)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01ed8)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0449d)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff81f3bb59)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3f6e4)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f6b5bc)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81fac0d3)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff81fe156b)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820245f0)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820283ca)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206abcc)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff82072c05)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
```
```
In net/mptcp/token.c (ffffffff82080380)
Location: include/net/sock.h:1528
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
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
In net/netlink/af_netlink.c (ffffffff81f8ab45)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc80e0)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc87c3)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
```
```
In net/ipv4/raw.c (ffffffff82001c79)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff82005614)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff8203199c)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff820794f3)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820af40d)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
  - net/ipv6/ipv6_sockglue.c:do_ipv6_setsockopt
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3900)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820f7c2a)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e2dc)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/protocol.c (ffffffff8214b940)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_listen
```
```
In net/mptcp/token.c (ffffffff82155870)
Location: include/net/sock.h:1503
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_accept
  - net/mptcp/token.c:mptcp_token_new_connect
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
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baafe0)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff800010baafe0-ffff800010bab030: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7a3c)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c0cc7a3c-c0cc7a70: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e250)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c000000000c7e250-c000000000c7e27c: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073c6de)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffe00073c6de-ffffffe00073c734: sock_prot_inuse_add (STB_GLOBAL)
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
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b17c0)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff818b17c0-ffffffff818b17e0: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b710)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff8186b710-ffffffff8186b730: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819027c0)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff819027c0-ffffffff819027e0: sock_prot_inuse_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_prot_inuse_add(struct net *net, struct proto *prot, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81923760)
Location: net/core/sock.c:3232
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_release
  - net/netlink/af_netlink.c:netlink_create
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/raw.c:raw_unhash_sk
  - net/ipv4/raw.c:raw_hash_sk
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_sock_destructor
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/packet/af_packet.c:packet_create
  - net/packet/af_packet.c:packet_release
  - net/xdp/xsk.c:xsk_create
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81923760-ffffffff81923780: sock_prot_inuse_add (STB_GLOBAL)
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
