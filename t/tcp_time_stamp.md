# Function: <code>tcp_time_stamp</code>

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
In net/ipv4/tcp_input.c (ffffffff81830ef4)
Location: include/net/tcp.h:731
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81835327)
Location: include/net/tcp.h:731
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81838739)
Location: include/net/tcp.h:731
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp_input.c (ffffffff818b0371)
Location: include/net/tcp.h:707
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff818b47ae)
Location: include/net/tcp.h:707
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7e75)
Location: include/net/tcp.h:707
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp_input.c (ffffffff8190552a)
Location: include/net/tcp.h:717
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81909ded)
Location: include/net/tcp.h:717
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d825)
Location: include/net/tcp.h:717
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
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
In net/ipv4/tcp_input.c (ffffffff819336d0)
Location: include/net/tcp.h:744
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819380a4)
Location: include/net/tcp.h:744
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8193bc0c)
Location: include/net/tcp.h:744
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timer_handler
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff8199706d)
Location: include/net/tcp.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff8199b4fd)
Location: include/net/tcp.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f4de)
Location: include/net/tcp.h:745
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff819cdbed)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819d1f1d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff819d608e)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81ab9db3)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81abee62)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2f9c)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81ac51f3)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81aca7c5)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81acea1c)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81ab042a)
Location: include/net/tcp.h:782
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5646)
Location: include/net/tcp.h:782
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9bbc)
Location: include/net/tcp.h:782
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81b6d25a)
Location: include/net/tcp.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81b72650)
Location: include/net/tcp.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76ff0)
Location: include/net/tcp.h:775
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81cfc9c0)
Location: include/net/tcp.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81d01d3a)
Location: include/net/tcp.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81d0691c)
Location: include/net/tcp.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81ec1570)
Location: include/net/tcp.h:802
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6eba)
Location: include/net/tcp.h:802
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbb7c)
Location: include/net/tcp.h:802
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff81f1fad0)
Location: include/net/tcp.h:797
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (ffffffff81f25776)
Location: include/net/tcp.h:797
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a846)
Location: include/net/tcp.h:797
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/ipv4/tcp_input.c (ffff800010c80768)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffff800010c84afc)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffff800010c890a0)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (c0d8fc3c)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_output.c (c0d93d8c)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (c0d98584)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (c000000000d8b3e0)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (c000000000d90994)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (c000000000d962c0)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffe0007e26e2)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6492)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea03c)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff8196da5d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff81971d8d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff81975efe)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff8192754d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff8192b85d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f9be)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff819d822d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819dc55d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff819e06ce)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
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
In net/ipv4/tcp_input.c (ffffffff819e1e6d)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_rcv_synsent_state_process
  - net/ipv4/tcp_input.c:tcp_rcv_established
  - net/ipv4/tcp_input.c:tcp_rcv_established
```
```
In net/ipv4/tcp_output.c (ffffffff819e61dd)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea38e)
Location: include/net/tcp.h:766
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
</details>
</li>
</ul>

## Differences
