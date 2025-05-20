# Function: <code>tcp_mss_clamp</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81835092)
Location: include/linux/tcp.h:452
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183be21)
Location: include/linux/tcp.h:452
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183d9fb)
Location: include/linux/tcp.h:452
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8185)
Location: include/linux/tcp.h:452
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff818b452a)
Location: include/linux/tcp.h:454
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818b9894)
Location: include/linux/tcp.h:454
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdac5)
Location: include/linux/tcp.h:454
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193b011)
Location: include/linux/tcp.h:454
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81909b3d)
Location: include/linux/tcp.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191014b)
Location: include/linux/tcp.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8191394f)
Location: include/linux/tcp.h:468
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81993a9b)
Location: include/linux/tcp.h:468
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81937de9)
Location: include/linux/tcp.h:482
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193e5cb)
Location: include/linux/tcp.h:482
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819420ff)
Location: include/linux/tcp.h:482
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819ca1af)
Location: include/linux/tcp.h:482
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8199b006)
Location: include/linux/tcp.h:475
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a2a1d)
Location: include/linux/tcp.h:475
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a6700)
Location: include/linux/tcp.h:475
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a38dc7)
Location: include/linux/tcp.h:475
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819d1a26)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d9602)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dcb20)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a6f937)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81abe986)
Location: include/linux/tcp.h:489
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac64ce)
Location: include/linux/tcp.h:489
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81aca641)
Location: include/linux/tcp.h:489
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6981f)
Location: include/linux/tcp.h:489
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81aca2e6)
Location: include/linux/tcp.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad37f2)
Location: include/linux/tcp.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad65b1)
Location: include/linux/tcp.h:501
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78289)
Location: include/linux/tcp.h:501
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ab5166)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abe88d)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac1621)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b671d2)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81b72156)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7c3bd)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f082)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2edcb)
Location: include/linux/tcp.h:502
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81d01847)
Location: include/linux/tcp.h:503
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0c2e9)
Location: include/linux/tcp.h:503
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0e9e6)
Location: include/linux/tcp.h:503
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcc1b6)
Location: include/linux/tcp.h:503
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81ec69b7)
Location: include/linux/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed1d29)
Location: include/linux/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed44c6)
Location: include/linux/tcp.h:540
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9d2c8)
Location: include/linux/tcp.h:540
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81f25179)
Location: include/linux/tcp.h:542
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f309fe)
Location: include/linux/tcp.h:542
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f334e8)
Location: include/linux/tcp.h:542
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffdd9a)
Location: include/linux/tcp.h:542
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81fe9a59)
Location: include/linux/tcp.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff690e)
Location: include/linux/tcp.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff9650)
Location: include/linux/tcp.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820ccc24)
Location: include/linux/tcp.h:598
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffff800010c84620)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8cbe8)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c8f71c)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38318)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (c0d938f4)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (c0d9cd10)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (c0d9f4a8)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (c0e3b61c)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (c000000000d902ec)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9bac8)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9ebe8)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6baa0)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffe0007e606c)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ebfce)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007efdbc)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008754fc)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff81971896)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81979472)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c990)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0efc7)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff8192b366)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932f32)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81936450)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cbd87)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819dc066)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e3c42)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e7160)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a79a47)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
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
In net/ipv4/tcp_output.c (ffffffff819e5ce6)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_connect_init
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819edd62)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_syn_recv_sock
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0e30)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_openreq_init_rwin
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a8623a)
Location: include/linux/tcp.h:477
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
```
</details>
</li>
</ul>

## Differences
