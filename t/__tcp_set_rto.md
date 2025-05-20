# Function: <code>__tcp_set_rto</code>

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
In net/ipv4/tcp_input.c (ffffffff8176d359)
Location: include/net/tcp.h:629
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_timer.c (ffffffff8177a539)
Location: include/net/tcp.h:629
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8177de1f)
Location: include/net/tcp.h:629
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff817db0fa)
Location: include/net/tcp.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_timer.c (ffffffff817e778d)
Location: include/net/tcp.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff817eb276)
Location: include/net/tcp.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff8180ac36)
Location: include/net/tcp.h:623
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_timer.c (ffffffff81817f29)
Location: include/net/tcp.h:623
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8181bbc6)
Location: include/net/tcp.h:623
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff8182a927)
Location: include/net/tcp.h:631
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff818383b7)
Location: include/net/tcp.h:631
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183c470)
Location: include/net/tcp.h:631
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff818aa4cb)
Location: include/net/tcp.h:607
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff818b7ad0)
Location: include/net/tcp.h:607
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bbba3)
Location: include/net/tcp.h:607
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff818ff7c4)
Location: include/net/tcp.h:617
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8190d47c)
Location: include/net/tcp.h:617
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8191170a)
Location: include/net/tcp.h:617
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff8192d556)
Location: include/net/tcp.h:644
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8193b862)
Location: include/net/tcp.h:644
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193feee)
Location: include/net/tcp.h:644
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff81990e62)
Location: include/net/tcp.h:645
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8199fc25)
Location: include/net/tcp.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a43fe)
Location: include/net/tcp.h:645
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff819c7a42)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819d67fc)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db01e)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff81ab49d1)
Location: include/net/tcp.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac3435)
Location: include/net/tcp.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac5086)
Location: include/net/tcp.h:671
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81abfa9e)
Location: include/net/tcp.h:677
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81aceeaa)
Location: include/net/tcp.h:677
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0a16)
Location: include/net/tcp.h:677
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81aa9db1)
Location: include/net/tcp.h:678
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81aba013)
Location: include/net/tcp.h:678
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abbaf3)
Location: include/net/tcp.h:678
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81b661a1)
Location: include/net/tcp.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81b77452)
Location: include/net/tcp.h:671
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78cc6)
Location: include/net/tcp.h:671
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81cf4495)
Location: include/net/tcp.h:685
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06d61)
Location: include/net/tcp.h:685
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08afd)
Location: include/net/tcp.h:685
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81eb8e65)
Location: include/net/tcp.h:698
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecbfc3)
Location: include/net/tcp.h:698
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdc3d)
Location: include/net/tcp.h:698
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81f17275)
Location: include/net/tcp.h:693
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2abe5)
Location: include/net/tcp.h:693
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c90d)
Location: include/net/tcp.h:693
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
In net/ipv4/tcp_input.c (ffffffff81fdc727)
Location: include/net/tcp.h:706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef804)
Location: include/net/tcp.h:706
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff181d)
Location: include/net/tcp.h:706
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
In net/ipv4/tcp_input.c (ffff800010c790c0)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffff800010c896f8)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e3b0)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (c0d89154)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack_update_rtt
```
```
In net/ipv4/tcp_timer.c (c0d987ac)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c0d9d40c)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (c000000000d83ed8)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (c000000000d96a44)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9ce20)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffe0007dd622)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffe0007ea5be)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee7da)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff819678b2)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8197666c)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197ae8e)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff819213a2)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff8193012c)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193494e)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff819d2082)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0e3c)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e565e)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
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
In net/ipv4/tcp_input.c (ffffffff819dbc22)
Location: include/net/tcp.h:666
Inline: True
```
```
In net/ipv4/tcp_timer.c (ffffffff819eaafc)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef30c)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
</details>
</li>
</ul>

## Differences
