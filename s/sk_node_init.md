# Function: <code>sk_node_init</code>

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
In net/core/sock.c (ffffffff81703dba)
Location: include/net/sock.h:554
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8176b2ec)
Location: include/net/sock.h:554
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff817843d1)
Location: include/net/sock.h:554
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/unix/af_unix.c (ffffffff817bfd5f)
Location: include/net/sock.h:554
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_bind
```
```
In net/packet/af_packet.c (ffffffff81805884)
Location: include/net/sock.h:554
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff8176a846)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:547
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff817d7ab7)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff817f1991)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff817f3deb)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff8182da21)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81876444)
Location: include/net/sock.h:547
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff81797966)
Location: include/net/sock.h:568
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:568
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81807a57)
Location: include/net/sock.h:568
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81822711)
Location: include/net/sock.h:568
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81824ffb)
Location: include/net/sock.h:568
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff8185f4e5)
Location: include/net/sock.h:568
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818aa944)
Location: include/net/sock.h:568
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff817b5521)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:582
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81828407)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81843361)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818475f9)
Location: include/net/sock.h:582
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81882d95)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff818d1455)
Location: include/net/sock.h:582
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
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
In net/core/sock.c (ffffffff8182d9ad)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/sock.h:586
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff818a791b)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff818c2d31)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff818c7059)
Location: include/net/sock.h:586
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81905145)
Location: include/net/sock.h:586
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81956375)
Location: include/net/sock.h:586
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
In net/core/sock.c (ffffffff81877d4e)
Location: include/net/sock.h:593
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff818f241a)
Location: include/net/sock.h:593
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/tcp_input.c (ffffffff818fca67)
Location: include/net/sock.h:593
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff8191881b)
Location: include/net/sock.h:593
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8191db43)
Location: include/net/sock.h:593
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8195a787)
Location: include/net/sock.h:593
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819b1795)
Location: include/net/sock.h:593
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
In net/core/sock.c (ffffffff8189822e)
Location: include/net/sock.h:613
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff8191fe1a)
Location: include/net/sock.h:613
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/tcp_input.c (ffffffff8192abd7)
Location: include/net/sock.h:613
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81946feb)
Location: include/net/sock.h:613
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff8194c0c3)
Location: include/net/sock.h:613
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198f477)
Location: include/net/sock.h:613
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819e8b75)
Location: include/net/sock.h:613
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
In net/core/sock.c (ffffffff818e2791)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_hashtables.c (ffffffff81982723)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_unhash
```
```
In net/ipv4/tcp_input.c (ffffffff8198de1c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff819ab66b)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819b08b0)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819fac89)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a58ee7)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a747cf)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffff81914961)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819c49ec)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff819e233b)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819e7543)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a31919)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a8eff7)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81aab185)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffff819e6edc)
Location: include/net/sock.h:657
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0af0)
Location: include/net/sock.h:657
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81acf93b)
Location: include/net/sock.h:657
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ad499c)
Location: include/net/sock.h:657
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b25e26)
Location: include/net/sock.h:657
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b8b3dc)
Location: include/net/sock.h:657
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba7629)
Location: include/net/sock.h:657
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
In net/core/sock.c (ffffffff819e6712)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81abbb40)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81adc21b)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81ae0edc)
Location: include/net/sock.h:664
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b347c4)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b9a3ac)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81bb6492)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff819cc51a)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff81aa6b00)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81ac718b)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81acc1fd)
Location: include/net/sock.h:664
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81b225d3)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81b89311)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ba5452)
Location: include/net/sock.h:664
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81a7bb79)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81b56bcd)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
```
```
In net/ipv4/tcp_input.c (ffffffff81b63100)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81b859ab)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81b8aa8d)
Location: include/net/sock.h:676
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81be9329)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81c55421)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81c72fd2)
Location: include/net/sock.h:676
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
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
In net/core/sock.c (ffffffff81befa03)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ce4a60)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
```
```
In net/ipv4/tcp_input.c (ffffffff81cf1dac)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81d19874)
Location: include/net/sock.h:715
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81d804a6)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81df51c1)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81e16d5f)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff81e37c10)
Location: include/net/sock.h:715
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/core/sock.c (ffffffff81d9c850)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81ea7970)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
```
```
In net/ipv4/tcp_input.c (ffffffff81eb661c)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/udp.c (ffffffff81ee01cf)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/unix/af_unix.c (ffffffff81f4b757)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff81fc7b41)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81fee72f)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82010e93)
Location: include/net/sock.h:746
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/core/sock.c (ffffffff81e0b0ac)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81f06120)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
```
```
In net/ipv4/tcp_input.c (ffffffff81f14a3c)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff81f3bb2d)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81f3f68f)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff81f6b579)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff81fab4f7)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff82028ad1)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8206a828)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff8208dc53)
Location: include/net/sock.h:748
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/core/sock.c (ffffffff81ec7a9c)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/inet_connection_sock.c (ffffffff81fca2d0)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/ipv4/inet_connection_sock.c:inet_reqsk_clone
```
```
In net/ipv4/tcp_input.c (ffffffff81fd8f5b)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff82001c4d)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff820055bf)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_lib_unhash
```
```
In net/ipv4/ping.c (ffffffff82031959)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_unhash
```
```
In net/unix/af_unix.c (ffffffff820788e7)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:unix_release_sock
  - net/unix/af_unix.c:__unix_set_addr_hash
```
```
In net/packet/af_packet.c (ffffffff820f8511)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff8213e459)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
```
In net/mctp/af_mctp.c (ffffffff82164113)
Location: include/net/sock.h:731
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sk_unhash
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
In net/core/sock.c (ffff800010bad780)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffff800010c7744c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffff800010c96dac)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffff800010c9b614)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffff800010cf2b74)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffff800010d5c21c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffff800010d7f084)
Location: include/net/sock.h:615
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
In net/core/sock.c (c0ccb318)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (c0d859b8)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (c0da4acc)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c0da83dc)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (c0df891c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c0e5c230)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c0e7923c)
Location: include/net/sock.h:615
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
In net/core/sock.c (c000000000c83060)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (c000000000d7f878)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (c000000000da78ec)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (c000000000dac8cc)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (c000000000e17fd0)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (c000000000e97c68)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (c000000000ebf2e4)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffe00073f994)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffe0007da5ec)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffe0007f53ca)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffe0007f99e2)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffe00083e1ea)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffe0008923d0)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffe0008ac214)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffff818b4961)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8196485c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff819821ab)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819873b3)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffff819d0fa9)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a2e687)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a4a515)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffff8186e8b1)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff8191e34c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff8193bc6b)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff81940e73)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8198dd69)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff819eb877)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81a07105)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffff81905961)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819cf02c)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff819ec97b)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819f1b83)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a3ba29)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81a9a237)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ab63c5)
Location: include/net/sock.h:615
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
In net/core/sock.c (ffffffff81926983)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/core/sock.c:sk_clone_lock
```
```
In net/ipv4/tcp_input.c (ffffffff819d8bbc)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:inet_reqsk_alloc
```
```
In net/ipv4/raw.c (ffffffff819f686b)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_unhash_sk
```
```
In net/ipv4/udp.c (ffffffff819fb473)
Location: include/net/sock.h:615
Inline: True
```
```
In net/unix/af_unix.c (ffffffff81a46d79)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_release_sock
```
```
In net/packet/af_packet.c (ffffffff81aa6f67)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_release
```
```
In net/xdp/xsk.c (ffffffff81ac24e5)
Location: include/net/sock.h:615
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_release
```
</details>
</li>
</ul>

## Differences
