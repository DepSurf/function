# Function: <code>inet_csk_exit_pingpong_mode</code>

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
In net/ipv4/tcp.c (ffffffff8198a5a1)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819972c4)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f33e)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff819beb48)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819cde44)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5ef0)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81aa8f0c)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
```
In net/ipv4/tcp_input.c (ffffffff81ab9fff)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2db0)
Location: include/net/inet_connection_sock.h:332
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81ab6cbc)
Location: include/net/inet_connection_sock.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
```
In net/ipv4/tcp_input.c (ffffffff81ac5441)
Location: include/net/inet_connection_sock.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace840)
Location: include/net/inet_connection_sock.h:327
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81aa336c)
Location: include/net/inet_connection_sock.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
```
In net/ipv4/tcp_input.c (ffffffff81ab0665)
Location: include/net/inet_connection_sock.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab99e0)
Location: include/net/inet_connection_sock.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81b5d044)
Location: include/net/inet_connection_sock.h:325
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b6d495)
Location: include/net/inet_connection_sock.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76e16)
Location: include/net/inet_connection_sock.h:325
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81ceba24)
Location: include/net/inet_connection_sock.h:331
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cfcaea)
Location: include/net/inet_connection_sock.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81d066d6)
Location: include/net/inet_connection_sock.h:331
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81eaf8b4)
Location: include/net/inet_connection_sock.h:334
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ec169a)
Location: include/net/inet_connection_sock.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb96e)
Location: include/net/inet_connection_sock.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff81f0dccd)
Location: include/net/inet_connection_sock.h:334
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81f1fbf9)
Location: include/net/inet_connection_sock.h:334
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a4ee)
Location: include/net/inet_connection_sock.h:334
Inline: True
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
In net/ipv4/tcp.c (ffffffff81fd1dd9)
Location: include/net/inet_connection_sock.h:336
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81fe4403)
Location: include/net/inet_connection_sock.h:336
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef069)
Location: include/net/inet_connection_sock.h:336
Inline: True
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
In net/ipv4/tcp.c (ffff800010c725f0)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c80920)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffff800010c88e50)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (c0d80f24)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (c0d8faf0)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (c0d97f6c)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (c000000000d7ac94)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d8b5f4)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (c000000000d95ff0)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffe0007d728a)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007e28a4)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9e76)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff8195e9b8)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8196dcb4)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff81975d60)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff819184a8)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819277a4)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f820)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff819c9188)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d8484)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0530)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In net/ipv4/tcp.c (ffffffff819d2cd8)
Location: include/net/inet_connection_sock.h:321
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819e20c4)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_send_dupack
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
  - net/ipv4/tcp_input.c:__tcp_ecn_check_ce
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea1f0)
Location: include/net/inet_connection_sock.h:321
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
</details>
</li>
</ul>

## Differences
