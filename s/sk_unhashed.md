# Function: <code>sk_unhashed</code>

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
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:544
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:544
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
In net/core/filter.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:537
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:537
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
In net/core/filter.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:558
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:558
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
In net/core/filter.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/inet_timewait_sock.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/inet_connection_sock.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/unix/af_unix.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/ipv6/inet6_hashtables.c (0)
Location: include/net/sock.h:572
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/net/sock.h:572
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
In net/core/filter.c (0)
Location: include/net/sock.h:576
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffffffff8189d5f8)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8189e82d)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:__inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818a08f5)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/raw.c (ffffffff818c2d12)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c7036)
Location: include/net/sock.h:576
Inline: True
```
```
In net/ipv4/ping.c (ffffffff818e4bbe)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81905125)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81953520)
Location: include/net/sock.h:576
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81956356)
Location: include/net/sock.h:576
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
In net/core/filter.c (ffffffff818b2f73)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/core/filter.c:__reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f30b1)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff818f342d)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff818f4b45)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/raw.c (ffffffff81918802)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191d8e5)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff8193b48e)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8195a76c)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819acf29)
Location: include/net/sock.h:583
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819b177c)
Location: include/net/sock.h:583
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
Location: include/net/sock.h:603
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff818e0da5)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81920ae2)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81920f4d)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81922045)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
  - net/ipv4/inet_connection_sock.c:inet_csk_reqsk_queue_drop
```
```
In net/ipv4/raw.c (ffffffff81946fd2)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c195)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff8196b17e)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8198f45c)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e38e4)
Location: include/net/sock.h:603
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819e8b5c)
Location: include/net/sock.h:603
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff8192f575)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff8198338a)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff8198391c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81985137)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819ab652)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b0bc5)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff819d1e4e)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff819fac70)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52617)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a58ecc)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a747b4)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff819617e5)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff819b9bfd)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ba10f)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819bb1e7)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819e2322)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e7b15)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81a089ae)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81a31900)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a89227)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a8efdc)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab16a)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:647
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81a34e15)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/core/sock_map.c (ffffffff81a4fb80)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_elem
  - net/core/sock_map.c:sock_map_update_elem
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aa47c4)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aa4b9f)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81aa60c7)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/raw.c (ffffffff81acf922)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad4a95)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81af7a0e)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81b25e06)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84357)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b8b3c1)
Location: include/net/sock.h:647
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba760e)
Location: include/net/sock.h:647
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
Location: include/net/sock.h:654
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81a37155)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/core/sock_map.c (ffffffff81a5599e)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/ipv4/inet_hashtables.c (ffffffff81aaee10)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81aaf1ff)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ab0717)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
  - net/ipv4/inet_connection_sock.c:reqsk_queue_unlink
```
```
In net/ipv4/raw.c (ffffffff81adc202)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0fd5)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81b048ee)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81b347ab)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93bb6)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b9a391)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb646b)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81bc60e5)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
Location: include/net/sock.h:654
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81a1e2b5)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/core/sock_map.c (ffffffff81a51475)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
```
In net/ipv4/inet_hashtables.c (ffffffff81a9a0c1)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81a9a512)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81a9b8f7)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81ac7172)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81accf35)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81af015e)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81b225ba)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82cc6)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81b892f6)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba542b)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81bb6c45)
Location: include/net/sock.h:654
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
Location: include/net/sock.h:666
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81ad1857)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81b55532)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81b55982)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56f27)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7a122)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/raw.c (ffffffff81b85992)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8b8b5)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81bb016e)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81be930d)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4ed96)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81c55406)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fab)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81c85c75)
Location: include/net/sock.h:666
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
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
Location: include/net/sock.h:705
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81c4f165)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ce3084)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ce3380)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4e85)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a2ad)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/raw.c (ffffffff81d159e2)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81d18c55)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81d42ade)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81d7c9be)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def697)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81df51a8)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d3b)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff81e2bf55)
Location: include/net/sock.h:705
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff81e37bf7)
Location: include/net/sock.h:705
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
Location: include/net/sock.h:736
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81e042d5)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81ea5516)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5cd5)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7ac5)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecfb2d)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/raw.c (ffffffff81edbd92)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81edf355)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f0b9ae)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81f49a3e)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3767)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81fc7b28)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee70b)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff82004195)
Location: include/net/sock.h:736
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff82010e78)
Location: include/net/sock.h:736
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
Location: include/net/sock.h:738
Inline: True
```
```
In net/core/filter.c (ffffffff81e70195)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/sock_reuseport.c (ffffffff81e76b25)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f03c9d)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81f0443f)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06305)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e7f8)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/raw.c (ffffffff81f3bb14)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3ec0c)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81f6b560)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81fa969e)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820245a7)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff82028ab8)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a80b)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff82080365)
Location: include/net/sock.h:738
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff8208dc38)
Location: include/net/sock.h:738
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
Location: include/net/sock.h:721
Inline: True
```
```
In net/core/filter.c (ffffffff81f2a3f6)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_assign
```
```
In net/core/sock_reuseport.c (ffffffff81f36ae5)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_prog
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc8108)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81fc8765)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca5f5)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff3658)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_show
```
```
In net/ipv4/raw.c (ffffffff82001c34)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff82004f6c)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_show
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_unhash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff82031940)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff82076b2e)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/unix/af_unix.c:bpf_iter_unix_seq_show
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f38b7)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff820f84f8)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e43c)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mptcp/token.c (ffffffff82155855)
Location: include/net/sock.h:721
Inline: True
Inline callers:
  - net/mptcp/token.c:mptcp_token_destroy
  - net/mptcp/token.c:mptcp_token_destroy
```
```
In net/mctp/af_mctp.c (ffffffff821640f8)
Location: include/net/sock.h:721
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffff800010c0528c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffff800010c6b494)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffff800010c6bb18)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffff800010c6c7c0)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffff800010c96d94)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c9ba60)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffff800010cc0c78)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffff800010cf2b5c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55ff8)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffff800010d5c204)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f06c)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (c0d1e588)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (c0d7a538)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c0d7a83c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c0d7bcac)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (c0da4ab0)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da7948)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (c0dcd360)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (c0df8900)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (c0e565e4)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c0e5c214)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e79220)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (c000000000cef454)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (c000000000d708cc)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (c000000000d70e28)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (c000000000d72a50)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (c000000000da78cc)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dab650)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (c000000000ddbfc0)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (c000000000e17fb0)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8f0a4)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (c000000000e97c44)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf2c0)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffe000783c78)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007d1094)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffe0007d153c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffe0007d20e4)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffe0007f53be)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f9d48)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffe000815f1a)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffe00083e1da)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d8b4)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffe0008923c4)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac208)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff819017b5)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff81959a6d)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81959f7f)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff8195b057)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff81982192)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81987985)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff819a874e)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff819d0f90)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a288b7)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a2e66c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a4fa)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff818bb5e5)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191355d)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81913a6f)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81914b47)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff8193bc52)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81941445)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff8196220e)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff8198dd50)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e5677)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff819eb85c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a070ea)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff819527e5)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff819c423d)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819c474f)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819c5827)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819ec962)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f2155)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81a12fee)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81a3ba10)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a94467)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81a9a21c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab63aa)
Location: include/net/sock.h:605
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
Location: include/net/sock.h:605
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff81974255)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_attach_prog
```
```
In net/ipv4/inet_hashtables.c (ffffffff819cdcaf)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:inet_unhash
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff819ce00d)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
  - net/ipv4/inet_timewait_sock.c:inet_twsk_kill
```
```
In net/ipv4/inet_connection_sock.c (ffffffff819cf307)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_destroy_sock
```
```
In net/ipv4/raw.c (ffffffff819f6852)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f9545)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_rehash
  - net/ipv4/udp.c:udp_lib_get_port
```
```
In net/ipv4/ping.c (ffffffff81a1d9be)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
  - net/ipv4/ping.c:ping_get_port
```
```
In net/unix/af_unix.c (ffffffff81a46d60)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_sock_destructor
  - net/unix/af_unix.c:__unix_insert_socket
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa05ac)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
```
In net/packet/af_packet.c (ffffffff81aa6f4c)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac24ca)
Location: include/net/sock.h:605
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
