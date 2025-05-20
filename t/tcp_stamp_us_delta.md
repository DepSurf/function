# Function: <code>tcp_stamp_us_delta</code>

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
In net/ipv4/tcp_input.c (ffffffff8182abb8)
Location: include/net/tcp.h:754
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81834577)
Location: include/net/tcp.h:754
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_rate.c (ffffffff8184194b)
Location: include/net/tcp.h:754
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81841ce1)
Location: include/net/tcp.h:754
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff818aa8c8)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff818b399b)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_rate.c (ffffffff818c1180)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff818c1505)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff818ffc38)
Location: include/net/tcp.h:740
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_output.c (ffffffff81909326)
Location: include/net/tcp.h:740
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_rate.c (ffffffff81916cbf)
Location: include/net/tcp.h:740
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81917095)
Location: include/net/tcp.h:740
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_input.c (ffffffff8192da07)
Location: include/net/tcp.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff819454a5)
Location: include/net/tcp.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff819458a5)
Location: include/net/tcp.h:757
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff8199166f)
Location: include/net/tcp.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff819a9aa6)
Location: include/net/tcp.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff819a9ea5)
Location: include/net/tcp.h:758
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff819c8255)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff819e0766)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0b65)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff81ab4da7)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81acdd39)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace155)
Location: include/net/tcp.h:790
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff81abfec8)
Location: include/net/tcp.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81ad9d99)
Location: include/net/tcp.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada155)
Location: include/net/tcp.h:796
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff81bba673)
Location: include/net/tcp.h:796
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffffffff81aadb24)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81ac4de5)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac51b5)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff81ba9903)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffffffff81b6a614)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81b835a2)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b839c5)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff81c78354)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffffffff81cf9798)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81d13c2d)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d140b5)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff81e1d414)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffffffff81ebe288)
Location: include/net/tcp.h:821
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81ed9c3d)
Location: include/net/tcp.h:821
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda105)
Location: include/net/tcp.h:821
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff81ff49c4)
Location: include/net/tcp.h:821
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffffffff81f1c728)
Location: include/net/tcp.h:816
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81f38d1d)
Location: include/net/tcp.h:816
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f391e5)
Location: include/net/tcp.h:816
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff82071284)
Location: include/net/tcp.h:816
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffffffff81fe0f08)
Location: include/net/tcp.h:840
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff81ffedfd)
Location: include/net/tcp.h:840
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff2d5)
Location: include/net/tcp.h:840
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
```
In net/mptcp/protocol.c (ffffffff8214488d)
Location: include/net/tcp.h:840
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In net/ipv4/tcp_input.c (ffff800010c7bd28)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffff800010c9451c)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94998)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (c0d896dc)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (c0da2d0c)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (c0da3228)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (c000000000d846d0)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (c000000000da4c1c)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (c000000000da51f8)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffe0007ddb94)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffe0007f3964)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3d4a)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff819680c5)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff819805d6)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff819809d5)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff81921bb5)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff8193a096)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a495)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff819d2895)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff819eada6)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb1a5)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff819dc435)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
  - net/ipv4/tcp_input.c:tcp_event_data_recv
  - net/ipv4/tcp_input.c:tcp_rcv_space_adjust
```
```
In net/ipv4/tcp_rate.c (ffffffff819f4c26)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f5025)
Location: include/net/tcp.h:779
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
```
</details>
</li>
</ul>

## Differences
