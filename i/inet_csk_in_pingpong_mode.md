# Function: <code>inet_csk_in_pingpong_mode</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819865e5)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8199726c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8199e76c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f2eb)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0a50)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a36bcb)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffff819bcd55)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819cddec)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819d527c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5e9d)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d7620)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d77d)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffff81aa7c15)
Location: include/net/inet_connection_sock.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9fb2)
Location: include/net/inet_connection_sock.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1bdc)
Location: include/net/inet_connection_sock.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2d5d)
Location: include/net/inet_connection_sock.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac45dd)
Location: include/net/inet_connection_sock.h:337
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66db3)
Location: include/net/inet_connection_sock.h:337
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81ab5a7a)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81ac53f4)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81acd641)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace7ed)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81acff1d)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b75313)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81aa0c5b)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0618)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8811)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab998d)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abaf7d)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b63bc3)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81b5caab)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d448)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81b75a31)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76dc3)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b782cd)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b683)
Location: include/net/inet_connection_sock.h:330
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81ceb452)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81cfc8a5)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81d052de)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81d0668c)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d07f76)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8c00)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81eb3c67)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81ec1455)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81eca3ae)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb912)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecca36)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f99900)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81f1281e)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81f1f9b5)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81f28eee)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a471)
Location: include/net/inet_connection_sock.h:339
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b716)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa2d0)
Location: include/net/inet_connection_sock.h:339
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffffffff81fd6df2)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4077)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff81feda1f)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81feefe1)
Location: include/net/inet_connection_sock.h:341
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0445)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:get_tcp4_sock
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c7f3e)
Location: include/net/inet_connection_sock.h:341
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:get_tcp6_sock
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
In net/ipv4/tcp.c (ffff800010c6f000)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffff800010c808d8)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffff800010c87eec)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffff800010c88dfc)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8a550)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d360c4)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (c0d7dbd4)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (c0d8faa4)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c0d97248)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (c0d97e68)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (c0d9a6d4)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (c0e38fd8)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (c000000000d75300)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (c000000000d8b5ac)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (c000000000d94ca4)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (c000000000d95f88)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (c000000000d98ce8)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (c000000000e684f0)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffe0007d3d7e)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffe0007e286e)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffe0007e9190)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9df4)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eb8cc)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000873746)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffff8195cbc5)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8196dc5c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819750ec)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff81975d0d)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81977490)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0ce0d)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffff819166b5)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8192774c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff8192ebac)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f7cd)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930f50)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819c9bcd)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffff819c7395)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819d842c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819df8bc)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff819e04dd)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1c60)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7788d)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv4/tcp.c (ffffffff819d0ee5)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819e206c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:__tcp_ack_snd_check
```
```
In net/ipv4/tcp_output.c (ffffffff819e956c)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_delayed_ack
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea19d)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb9b0)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a83ffd)
Location: include/net/inet_connection_sock.h:326
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
</ul>

## Differences
