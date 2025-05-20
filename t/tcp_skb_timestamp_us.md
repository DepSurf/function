# Function: <code>tcp_skb_timestamp_us</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8192d7d0)
Location: include/net/tcp.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81935e67)
Location: include/net/tcp.h:768
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193fe61)
Location: include/net/tcp.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff819453f6)
Location: include/net/tcp.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff8194569b)
Location: include/net/tcp.h:768
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81991230)
Location: include/net/tcp.h:769
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81999124)
Location: include/net/tcp.h:769
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4366)
Location: include/net/tcp.h:769
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff819a99f6)
Location: include/net/tcp.h:769
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9ca0)
Location: include/net/tcp.h:769
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff819c7e00)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819cfc44)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819daf86)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff819e06b6)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0960)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81ab4b60)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81abc2aa)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4ff4)
Location: include/net/tcp.h:801
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdc86)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81acdede)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81abfc56)
Location: include/net/tcp.h:807
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7b1d)
Location: include/net/tcp.h:807
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad0984)
Location: include/net/tcp.h:807
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9ce6)
Location: include/net/tcp.h:807
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ad9f40)
Location: include/net/tcp.h:807
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81aac03c)
Location: include/net/tcp.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2b7d)
Location: include/net/tcp.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abba61)
Location: include/net/tcp.h:812
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4d39)
Location: include/net/tcp.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac4fa6)
Location: include/net/tcp.h:812
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81b6851c)
Location: include/net/tcp.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b6fa71)
Location: include/net/tcp.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b78c37)
Location: include/net/tcp.h:805
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81b834e9)
Location: include/net/tcp.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b837b6)
Location: include/net/tcp.h:805
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81cf7669)
Location: include/net/tcp.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81cff0f1)
Location: include/net/tcp.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d08a4d)
Location: include/net/tcp.h:819
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81d13b10)
Location: include/net/tcp.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d13e7c)
Location: include/net/tcp.h:819
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81ebc109)
Location: include/net/tcp.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ec4151)
Location: include/net/tcp.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdb8d)
Location: include/net/tcp.h:832
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed9b10)
Location: include/net/tcp.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ed9e9c)
Location: include/net/tcp.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81f1a599)
Location: include/net/tcp.h:827
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81f22456)
Location: include/net/tcp.h:827
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2c85d)
Location: include/net/tcp.h:827
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38bf0)
Location: include/net/tcp.h:827
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f38f7c)
Location: include/net/tcp.h:827
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81fded69)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81fe72f4)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81fef94e)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff176d)
Location: include/net/tcp.h:846
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffecd0)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff05c)
Location: include/net/tcp.h:846
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffff800010c7b8b0)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c82e3c)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8e324)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffff800010c94428)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94738)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (c0d89934)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d9184c)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (c0d9d380)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (c0da2bf4)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (c0da3068)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
  - net/ipv4/tcp_recovery.c:tcp_rack_skb_timeout
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
In net/ipv4/tcp_input.c (c000000000d849c4)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d8dd10)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9cd3c)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (c000000000da4b38)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (c000000000da4f28)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffe0007dd98a)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e4630)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007ee72e)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f38a2)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3b50)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81967c70)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8196fab4)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197adf6)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff81980526)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819807d0)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff81921760)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81929584)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819348b6)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff81939fe6)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a290)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff819d2440)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819da284)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e55c6)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff819eacf6)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eafa0)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff819dbfe0)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e3efe)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819ef274)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_err
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4b76)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
  - net/ipv4/tcp_rate.c:tcp_rate_skb_sent
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f4e20)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
</details>
</li>
</ul>

## Differences
