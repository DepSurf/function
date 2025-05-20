# Function: <code>tcp_ns_to_ts</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aaa7c8)
Location: include/net/tcp.h:777
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab5021)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81ac0c18)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8960)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81b07255)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a4b7)
Location: include/net/tcp.h:777
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81ab77aa)
Location: include/net/tcp.h:783
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ac014b)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81acc688)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad4900)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81b15628)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78fae)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81aa29a8)
Location: include/net/tcp.h:788
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81aaa004)
Location: include/net/tcp.h:788
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7848)
Location: include/net/tcp.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf9b6)
Location: include/net/tcp.h:788
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81b03435)
Location: include/net/tcp.h:788
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67af8)
Location: include/net/tcp.h:788
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81b5eb53)
Location: include/net/tcp.h:781
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b663f4)
Location: include/net/tcp.h:781
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b74a68)
Location: include/net/tcp.h:781
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d51d)
Location: include/net/tcp.h:781
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81bc56c5)
Location: include/net/tcp.h:781
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f724)
Location: include/net/tcp.h:781
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81ced773)
Location: include/net/tcp.h:795
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cf46fd)
Location: include/net/tcp.h:795
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81d041c8)
Location: include/net/tcp.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d478)
Location: include/net/tcp.h:795
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81d5a8a5)
Location: include/net/tcp.h:795
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccb1f)
Location: include/net/tcp.h:795
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81eb3f9d)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81eb90dd)
Location: include/net/tcp.h:808
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9128)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2ead)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81f24cf5)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dc32)
Location: include/net/tcp.h:808
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81f12913)
Location: include/net/tcp.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f174ed)
Location: include/net/tcp.h:803
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f27c48)
Location: include/net/tcp.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_established_options
  - net/ipv4/tcp_output.c:tcp_synack_options
  - net/ipv4/tcp_output.c:tcp_syn_options
```
```
In net/ipv4/tcp_timer.c (ffffffff81f2a86f)
Location: include/net/tcp.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_retransmit_timer
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31ba7)
Location: include/net/tcp.h:803
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81f84885)
Location: include/net/tcp.h:803
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe768)
Location: include/net/tcp.h:803
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8204b0d5)
Location: net/ipv4/syncookies.c:55
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
