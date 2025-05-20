# Function: <code>tcp_time_stamp_raw</code>

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
In net/ipv4/tcp.c (ffffffff81823571)
Location: include/net/tcp.h:737
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8183cd55)
Location: include/net/tcp.h:737
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff8186e04d)
Location: include/net/tcp.h:737
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b8c7e)
Location: include/net/tcp.h:737
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff818a29a3)
Location: include/net/tcp.h:713
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff818bc477)
Location: include/net/tcp.h:713
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff818ee9dd)
Location: include/net/tcp.h:713
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193bb40)
Location: include/net/tcp.h:713
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff818f804f)
Location: include/net/tcp.h:723
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81911e66)
Location: include/net/tcp.h:723
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff819452e5)
Location: include/net/tcp.h:723
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81994da2)
Location: include/net/tcp.h:723
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff8192489c)
Location: include/net/tcp.h:750
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940637)
Location: include/net/tcp.h:750
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81975685)
Location: include/net/tcp.h:750
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb68e)
Location: include/net/tcp.h:750
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81987d66)
Location: include/net/tcp.h:751
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4b81)
Location: include/net/tcp.h:751
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff819df1a5)
Location: include/net/tcp.h:751
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a116)
Location: include/net/tcp.h:751
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff819be2fe)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db881)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81a16235)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70cb1)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81aaa7c3)
Location: include/net/tcp.h:783
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8955)
Location: include/net/tcp.h:783
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a4a5)
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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab77a5)
Location: include/net/tcp.h:789
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad48f5)
Location: include/net/tcp.h:789
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78fae)
Location: include/net/tcp.h:789
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
In net/ipv4/tcp.c (ffffffff81aa29a3)
Location: include/net/tcp.h:794
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf9ab)
Location: include/net/tcp.h:794
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67af8)
Location: include/net/tcp.h:794
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
In net/ipv4/tcp.c (ffffffff81b5eb4e)
Location: include/net/tcp.h:787
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d518)
Location: include/net/tcp.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f71f)
Location: include/net/tcp.h:787
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
In net/ipv4/tcp.c (ffffffff81ced76e)
Location: include/net/tcp.h:801
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d462)
Location: include/net/tcp.h:801
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccb1a)
Location: include/net/tcp.h:801
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
In net/ipv4/tcp.c (ffffffff81eb3f98)
Location: include/net/tcp.h:814
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2ea8)
Location: include/net/tcp.h:814
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dc2d)
Location: include/net/tcp.h:814
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
In net/ipv4/tcp.c (ffffffff81f1290e)
Location: include/net/tcp.h:809
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31ba2)
Location: include/net/tcp.h:809
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe763)
Location: include/net/tcp.h:809
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffff800010c72520)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec0c)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffff800010cd1f00)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39160)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 tcp_time_stamp_raw();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7f084)
Location: include/net/tcp.h:772
Inline: False
```
```
In net/ipv4/tcp_ipv4.c (c0d9c14c)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (c0ddbd8c)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (c0e39ee4)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
```
**Symbols:**

```
c0d7f084-c0d7f0e0: tcp_time_stamp_raw (STB_LOCAL)
c0d9bfec-c0d9c048: tcp_time_stamp_raw (STB_LOCAL)
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
In net/ipv4/tcp.c (c000000000d7956c)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d760)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (c000000000df02b0)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c724)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffe0007d52c6)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeef6)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffe000823304)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008764ee)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff8195e16e)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b6f1)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff819b58c5)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10341)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff81917c5e)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819351b1)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff819726b5)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd101)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff819c893e)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ec1)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81a20165)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7adc1)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In net/ipv4/tcp.c (ffffffff819d248e)
Location: include/net/tcp.h:772
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efb81)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81a2b665)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87601)
Location: include/net/tcp.h:772
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
