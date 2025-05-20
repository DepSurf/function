# Function: <code>sk_hashed</code>

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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:549
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:549
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:542
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:542
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:563
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:563
Inline: True
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
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:577
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:577
Inline: True
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
In net/ipv4/inet_hashtables.c (ffffffff8189d5f8)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e82d)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a08f5)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/raw.c (ffffffff818c2d12)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c7036)
Location: include/net/sock.h:581
Inline: True
```
```
In net/ipv4/ping.c (ffffffff818e4bbe)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81905125)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953520)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81956356)
Location: include/net/sock.h:581
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/ipv4/inet_hashtables.c (ffffffff818f237d)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f342d)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4d95)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/raw.c (ffffffff81918802)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191d8e5)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff8193b48e)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff8195a76c)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf4e)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819b177c)
Location: include/net/sock.h:588
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In kernel/bpf/reuseport_array.c (ffffffff811e28e4)
Location: include/net/sock.h:608
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fd7d)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920f4d)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922fc5)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/raw.c (ffffffff81946fd2)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c195)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff8196b17e)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff8198f45c)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e3909)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819e8b5c)
Location: include/net/sock.h:608
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In kernel/bpf/reuseport_array.c (ffffffff811f9a5f)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8198268d)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8198391c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985965)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819ab652)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b0bc5)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff819d1e4e)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff819fac70)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a5263f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a58ecc)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a747b4)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff81206b2f)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b8f0f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba10f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bbe05)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819e2322)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e7b15)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81a089ae)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81a31900)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a8924f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a8efdc)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab16a)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff8122f0f3)
Location: include/net/sock.h:652
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a4fb80)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa39d6)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b9f)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa68cd)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/raw.c (ffffffff81acf922)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad4a95)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81af7a0e)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81b25e06)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b8437f)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b8b3c1)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba760e)
Location: include/net/sock.h:652
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff81237613)
Location: include/net/sock.h:659
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a5599e)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aae016)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf1ff)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0f1d)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/raw.c (ffffffff81adc202)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0fd5)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81b048ee)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81b347ab)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93bde)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b9a391)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb646b)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81bc6142)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In kernel/bpf/reuseport_array.c (ffffffff8123be33)
Location: include/net/sock.h:659
Inline: True
```
```
In net/core/sock_map.c (ffffffff81a51475)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a990f6)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a512)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9c276)
Location: include/net/sock.h:659
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81ac7172)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81accf35)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81af015e)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81b225ba)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82cee)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b892f6)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba542b)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81bb6ca2)
Location: include/net/sock.h:659
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In kernel/bpf/reuseport_array.c (ffffffff812767c3)
Location: include/net/sock.h:671
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b54573)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55982)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b57b36)
Location: include/net/sock.h:671
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b85992)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8b8b5)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81bb016e)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81be930d)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4edbe)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81c55406)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fab)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81c85cd2)
Location: include/net/sock.h:671
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
In kernel/bpf/reuseport_array.c (ffffffff812c6247)
Location: include/net/sock.h:710
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce25f7)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3380)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce5b36)
Location: include/net/sock.h:710
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81d159e2)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81d18c55)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81d42ade)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81d8048d)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def6bf)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81df51a8)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d3b)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81e2bfb6)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff81e37bf7)
Location: include/net/sock.h:710
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/reuseport_array.c (ffffffff8132b9b7)
Location: include/net/sock.h:741
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea3678)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5cd5)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea8d25)
Location: include/net/sock.h:741
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edbd92)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81edf355)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff81f0b9ae)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81f4b73e)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc378f)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81fc7b28)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee70b)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff820041f6)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff82010e78)
Location: include/net/sock.h:741
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/reuseport_array.c (ffffffff8135bb27)
Location: include/net/sock.h:743
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f01ecf)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0443f)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f075a5)
Location: include/net/sock.h:743
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3bb14)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3e825)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff81f6b560)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81fab4de)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820245cf)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff82028ab8)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a80b)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff820803ee)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff8208dc38)
Location: include/net/sock.h:743
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/reuseport_array.c (ffffffff813847b7)
Location: include/net/sock.h:726
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc8108)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8765)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fcb905)
Location: include/net/sock.h:726
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82001c34)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff82004b75)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff82031940)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff820788ce)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f38df)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820f84f8)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e43c)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff821558de)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff821640f8)
Location: include/net/sock.h:726
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
  - net/mctp/af_mctp.c:mctp_bind
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
In kernel/bpf/reuseport_array.c (ffff800010290324)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6a80c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bb18)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6d2c0)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffff800010c96d94)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c9ba60)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffff800010cc0c78)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffff800010cf2b5c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d5601c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffff800010d5c204)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f06c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (c04bf94c)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (c0d79904)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a83c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7c284)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (c0da4ab0)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da7948)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (c0dcd360)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (c0df8900)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (c0e56618)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c0e5c214)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e79220)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (c00000000033d184)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (c000000000d6f9b0)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70e28)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d73258)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (c000000000da78cc)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dab650)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (c000000000ddbfc0)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (c000000000e17fb0)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f0dc)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c000000000e97c44)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf2c0)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffe0001c2ea0)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d0322)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d153c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d2fa0)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffe0007f53be)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f9d48)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffe000815f1a)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffe00083e1da)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d8e2)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe0008923c4)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac208)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff811ff14f)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff81958d7f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959f7f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195bc75)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81982192)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81987985)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff819a874e)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff819d0f90)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a288df)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a2e66c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a4fa)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff811f1e9f)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191286f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913a6f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81915765)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffff8193bc52)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81941445)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff8196220e)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff8198dd50)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e569f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819eb85c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a070ea)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff811fcf1f)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c354f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c474f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c6445)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819ec962)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f2155)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81a12fee)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81a3ba10)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a9448f)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a9a21c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab63aa)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In kernel/bpf/reuseport_array.c (ffffffff8120bbcf)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cd220)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce00d)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cff65)
Location: include/net/sock.h:610
Inline: True
```
```
In net/ipv4/raw.c (ffffffff819f6852)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f9545)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
```
```
In net/ipv4/ping.c (ffffffff81a1d9be)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81a46d60)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa05d5)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81aa6f4c)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac24ca)
Location: include/net/sock.h:610
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
