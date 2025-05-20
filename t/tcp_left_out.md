# Function: <code>tcp_left_out</code>

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
In net/ipv4/tcp_input.c (ffffffff8176ad18)
Location: include/net/tcp.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81778cc4)
Location: include/net/tcp.h:978
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
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
In net/ipv4/tcp_input.c (ffffffff817db5ee)
Location: include/net/tcp.h:997
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817e5e87)
Location: include/net/tcp.h:997
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_xmit_retransmit_queue
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
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
In net/ipv4/tcp_input.c (ffffffff8180b132)
Location: include/net/tcp.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818123d6)
Location: include/net/tcp.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
```
```
In net/ipv4/tcp_rate.c (ffffffff81821189)
Location: include/net/tcp.h:1052
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_check_app_limited
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
In net/ipv4/tcp_input.c (ffffffff8182b087)
Location: include/net/tcp.h:1087
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8183671f)
Location: include/net/tcp.h:1087
Inline: True
```
```
In net/ipv4/tcp_rate.c (ffffffff818417d9)
Location: include/net/tcp.h:1087
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:1087
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
In net/ipv4/tcp_input.c (ffffffff818aace5)
Location: include/net/tcp.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818b0ecc)
Location: include/net/tcp.h:1078
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
```
```
In net/ipv4/tcp_rate.c (ffffffff818c0ff9)
Location: include/net/tcp.h:1078
Inline: True
```
```
In net/ipv4/tcp_recovery.c (0)
Location: include/net/tcp.h:1078
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff8190035c)
Location: include/net/tcp.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81908a81)
Location: include/net/tcp.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81916b3d)
Location: include/net/tcp.h:1095
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81917134)
Location: include/net/tcp.h:1095
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff8192a76c)
Location: include/net/tcp.h:1135
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81936cd5)
Location: include/net/tcp.h:1135
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819452ed)
Location: include/net/tcp.h:1135
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81945944)
Location: include/net/tcp.h:1135
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff8198d9d9)
Location: include/net/tcp.h:1137
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8199c2cb)
Location: include/net/tcp.h:1137
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819a98ed)
Location: include/net/tcp.h:1137
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9f42)
Location: include/net/tcp.h:1137
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff819c458b)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819d2d6b)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819e05ad)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0c02)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81ab32cb)
Location: include/net/tcp.h:1178
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abfa40)
Location: include/net/tcp.h:1178
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdb7d)
Location: include/net/tcp.h:1178
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace1f2)
Location: include/net/tcp.h:1178
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81abe234)
Location: include/net/tcp.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_timeout_mark_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81acb4b5)
Location: include/net/tcp.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9bdd)
Location: include/net/tcp.h:1183
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada1f5)
Location: include/net/tcp.h:1183
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81aa9314)
Location: include/net/tcp.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6563)
Location: include/net/tcp.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_tso_should_defer
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4c2d)
Location: include/net/tcp.h:1175
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac5255)
Location: include/net/tcp.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81b65200)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81b7391a)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81b833dd)
Location: include/net/tcp.h:1168
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b83a65)
Location: include/net/tcp.h:1168
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81cf9a79)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81d02ff6)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81d139ed)
Location: include/net/tcp.h:1186
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d14184)
Location: include/net/tcp.h:1186
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81ebe589)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7fbf)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed99cd)
Location: include/net/tcp.h:1199
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda1e4)
Location: include/net/tcp.h:1199
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81f1ca29)
Location: include/net/tcp.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81f26a41)
Location: include/net/tcp.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38aad)
Location: include/net/tcp.h:1197
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f392c4)
Location: include/net/tcp.h:1197
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff81fe120c)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81feb429)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffeb8d)
Location: include/net/tcp.h:1234
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff3b4)
Location: include/net/tcp.h:1234
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffff800010c76fb8)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c85924)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffff800010c942d0)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94a38)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (c0d85514)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (c0d94b48)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (c0da2a5c)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (c0da32dc)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (c000000000d7f23c)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (c000000000d92258)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (c000000000da49a0)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (c000000000da52b4)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffe0007da212)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffe0007e7684)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f37c2)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3dc4)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff819643fb)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81972bdb)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff8198041d)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff81980a72)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff8191deeb)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8192c6ab)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff81939edd)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a532)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff819cebcb)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819dd3ab)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819eabed)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb242)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
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
In net/ipv4/tcp_input.c (ffffffff819d875b)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_try_keep_open
  - net/ipv4/tcp_input.c:tcp_cwnd_reduction
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_enter_loss
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819e702b)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4a6d)
Location: include/net/tcp.h:1158
Inline: True
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f50c2)
Location: include/net/tcp.h:1158
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
  - net/ipv4/tcp_recovery.c:tcp_rack_reo_timeout
```
</details>
</li>
</ul>

## Differences
