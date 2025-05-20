# Function: <code>memcpy_from_msg</code>

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
In net/netlink/af_netlink.c (ffffffff8174e868)
Location: include/linux/skbuff.h:2843
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81785399)
Location: include/linux/skbuff.h:2843
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff817a32b9)
Location: include/linux/skbuff.h:2843
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff817e62d1)
Location: include/linux/skbuff.h:2843
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff8180866a)
Location: include/linux/skbuff.h:2843
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff817baacd)
Location: include/linux/skbuff.h:3050
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff817f29d9)
Location: include/linux/skbuff.h:3050
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff818102d9)
Location: include/linux/skbuff.h:3050
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff818546ad)
Location: include/linux/skbuff.h:3050
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff8187a4ca)
Location: include/linux/skbuff.h:3050
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff817ea46d)
Location: include/linux/skbuff.h:3102
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81823794)
Location: include/linux/skbuff.h:3102
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff818417ce)
Location: include/linux/skbuff.h:3102
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff818863d6)
Location: include/linux/skbuff.h:3102
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818aed4d)
Location: include/linux/skbuff.h:3102
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff8180a145)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff818440d8)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81863462)
Location: include/linux/skbuff.h:3174
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818ac3b0)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff818d3b9a)
Location: include/linux/skbuff.h:3174
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff818890c5)
Location: include/linux/skbuff.h:3295
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff818c3a20)
Location: include/linux/skbuff.h:3295
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff818e35a2)
Location: include/linux/skbuff.h:3295
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f0d6)
Location: include/linux/skbuff.h:3295
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff8195a2fa)
Location: include/linux/skbuff.h:3295
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff818dca79)
Location: include/linux/skbuff.h:3305
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff819199c2)
Location: include/linux/skbuff.h:3305
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81939e3c)
Location: include/linux/skbuff.h:3305
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81988023)
Location: include/linux/skbuff.h:3305
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819b1c06)
Location: include/linux/skbuff.h:3305
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff8190945c)
Location: include/linux/skbuff.h:3384
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81947f02)
Location: include/linux/skbuff.h:3384
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81969c8c)
Location: include/linux/skbuff.h:3384
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819be959)
Location: include/linux/skbuff.h:3384
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff819e6566)
Location: include/linux/skbuff.h:3384
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff8196a775)
Location: include/linux/skbuff.h:3475
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff819accf9)
Location: include/linux/skbuff.h:3475
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819d0953)
Location: include/linux/skbuff.h:3475
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2d9ef)
Location: include/linux/skbuff.h:3475
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
```
```
In net/packet/af_packet.c (ffffffff81a56f94)
Location: include/linux/skbuff.h:3475
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff819a11e4)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff819e38ad)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a074a3)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6455a)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a8c00a)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff81a7ab1c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81ad1155)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81af6d13)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b5cfc0)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b88b4a)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff81a83972)
Location: include/linux/skbuff.h:3594
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81add0b1)
Location: include/linux/skbuff.h:3594
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81b03ba3)
Location: include/linux/skbuff.h:3594
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b6b801)
Location: include/linux/skbuff.h:3594
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b98637)
Location: include/linux/skbuff.h:3594
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff81a6ca5f)
Location: include/linux/skbuff.h:3659
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81ac811f)
Location: include/linux/skbuff.h:3659
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81aef7e3)
Location: include/linux/skbuff.h:3659
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81b59b48)
Location: include/linux/skbuff.h:3659
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81b875b8)
Location: include/linux/skbuff.h:3659
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff81b260bc)
Location: include/linux/skbuff.h:3696
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81b86988)
Location: include/linux/skbuff.h:3696
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81baf7e4)
Location: include/linux/skbuff.h:3696
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81c2116e)
Location: include/linux/skbuff.h:3696
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81c52fbf)
Location: include/linux/skbuff.h:3696
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff81caece5)
Location: include/linux/skbuff.h:4069
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81d173e5)
Location: include/linux/skbuff.h:4069
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81d42ce8)
Location: include/linux/skbuff.h:4069
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81dbdec4)
Location: include/linux/skbuff.h:4069
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81df76d8)
Location: include/linux/skbuff.h:4069
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff81e37277)
Location: include/linux/skbuff.h:4069
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/netlink/af_netlink.c (ffffffff81e6c335)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81eddc22)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81f0bcc8)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81f8e45f)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81fcbe13)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff820100b7)
Location: include/linux/skbuff.h:3965
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/netlink/af_netlink.c (ffffffff81ec8395)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff81f3ced1)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff81f6b938)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff81feed42)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff8202d11c)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff8208ccea)
Location: include/linux/skbuff.h:3997
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/netlink/af_netlink.c (ffffffff81f8b75b)
Location: include/linux/skbuff.h:4026
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff82003146)
Location: include/linux/skbuff.h:4026
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (ffffffff82031ef8)
Location: include/linux/skbuff.h:4026
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_common_sendmsg
```
```
In net/ipv6/raw.c (ffffffff820bc909)
Location: include/linux/skbuff.h:4026
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff820fcba3)
Location: include/linux/skbuff.h:4026
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
```
In net/mctp/af_mctp.c (ffffffff821631b7)
Location: include/linux/skbuff.h:4026
Inline: True
Inline callers:
  - net/mctp/af_mctp.c:mctp_sendmsg
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
In net/netlink/af_netlink.c (ffff800010c4f87c)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffff800010c98388)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffff800010cc03ec)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d2a44c)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffff800010d5889c)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (c0d5fa28)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (c0da6250)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv4/ping.c (c0dcc714)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (c0e2e4b0)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c0e594cc)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (c000000000d4e210)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (c000000000da9754)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (c000000000ddb610)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5b578)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (c000000000e93af8)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffe0007bb48e)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffe0007f6668)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffe000816c70)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086ac7c)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffe0008909ac)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff81941054)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff8198371d)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff819a7243)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a03bea)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a2b69a)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff818fab44)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff8193d1dd)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81960d03)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c09aa)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff819e888a)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff819921e4)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff819edeed)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a11ae3)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6e66a)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81a9724a)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
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
In net/netlink/af_netlink.c (ffffffff819b4cd4)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/ipv4/raw.c (ffffffff819f7e25)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv4/ping.c (ffffffff81a1c453)
Location: include/linux/skbuff.h:3542
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7ac9c)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
```
In net/packet/af_packet.c (ffffffff81aa3b67)
Location: include/linux/skbuff.h:3542
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg_spkt
```
</details>
</li>
</ul>

## Differences
