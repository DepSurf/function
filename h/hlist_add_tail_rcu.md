# Function: <code>hlist_add_tail_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cf2a5)
Location: include/linux/rculist.h:509
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff817f4b3c)
Location: include/linux/rculist.h:509
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff818750fa)
Location: include/linux/rculist.h:509
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/inet_hashtables.c (ffffffff817ff097)
Location: include/linux/rculist.h:507
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81825d8e)
Location: include/linux/rculist.h:507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff818a95d0)
Location: include/linux/rculist.h:507
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/inet_hashtables.c (ffffffff8181f353)
Location: include/linux/rculist.h:507
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81847d51)
Location: include/linux/rculist.h:507
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff818d0303)
Location: include/linux/rculist.h:507
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In net/ipv4/inet_hashtables.c (ffffffff8189e2b3)
Location: include/linux/rculist.h:508
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff818c77db)
Location: include/linux/rculist.h:508
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff8195521d)
Location: include/linux/rculist.h:508
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In security/security.c (ffffffff82715f75)
Location: include/linux/rculist.h:521
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f2cbf)
Location: include/linux/rculist.h:521
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff8191e9d8)
Location: include/linux/rculist.h:521
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff819aedf6)
Location: include/linux/rculist.h:521
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In security/security.c (ffffffff828cda38)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff8192073a)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff8194d7ee)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff819e579e)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
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
In security/security.c (ffffffff828e7464)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff81983081)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff819b1ff4)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81a551db)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a7472d)
Location: include/linux/rculist.h:536
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff828effd8)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b994a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff819e8d7a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81a8bdcb)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81aab0dc)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff82d05241)
Location: include/linux/rculist.h:587
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa43c0)
Location: include/linux/rculist.h:587
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81ad7025)
Location: include/linux/rculist.h:587
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81b891f9)
Location: include/linux/rculist.h:587
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ba707c)
Location: include/linux/rculist.h:587
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff82ff260e)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaea02)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81ae3605)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81b98cf9)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81bb63bb)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff831fcfea)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a99c54)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81ace60e)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81b87bfd)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ba6727)
Location: include/linux/rculist.h:616
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff832e41eb)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b550bc)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81b8cfda)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81c5412a)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81c74277)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff8349ad4c)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/udp.c (ffffffff81d1b616)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81df34ba)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81e17b19)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff81e37b77)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In security/security.c (ffffffff83ed1a0d)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/udp.c (ffffffff81ee2009)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81fc827a)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81feeac9)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff82010de7)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In security/security.c (ffffffff836f6aed)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/raw.c (ffffffff81f3bcb7)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff81f41a2d)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f6c673)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/packet/af_packet.c (ffffffff8202839f)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff8206ac08)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff8208d65b)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In security/security.c (ffffffff83929e97)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/raw.c (ffffffff82001dd7)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_hash_sk
```
```
In net/ipv4/udp.c (ffffffff8200768d)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff82032dc3)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_get_port
```
```
In net/packet/af_packet.c (ffffffff820f7bff)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff8213e318)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
```
In net/mctp/af_mctp.c (ffffffff82163b1b)
Location: include/linux/rculist.h:615
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_hash
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
In security/security.c (ffff800011469ec8)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b0d4)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffff800010c9c298)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffff800010d586a0)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffff800010d7e770)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (c1542aa0)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (c0d7a1ac)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (c0da89b4)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (c0e5813c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (c0e79178)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (c0000000013982e4)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (c000000000d70590)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (c000000000dae3a4)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (c000000000e90ce0)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (c000000000ebe7b0)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffe00002503a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0db2)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffe0007fb278)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffe000890654)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffe0008ac11c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff828d8e8c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff819597ba)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff81988bea)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81a2b45b)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a4a46c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff828d15a8)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff819132aa)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff819426aa)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff819e864b)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81a0705c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff828ebc0c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c3f8a)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff819f33ba)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81a9700b)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ab631c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
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
In security/security.c (ffffffff828f1022)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd9fa)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
```
In net/ipv4/udp.c (ffffffff819fbc90)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_get_port
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/packet/af_packet.c (ffffffff81aa209b)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_create
```
```
In net/xdp/xsk.c (ffffffff81ac243c)
Location: include/linux/rculist.h:556
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_create
```
</details>
</li>
</ul>

## Differences
