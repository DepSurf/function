# Function: <code>skb_set_dst_pending_confirm</code>

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
In net/ipv4/ip_output.c (ffffffff81818f4a)
Location: include/linux/skbuff.h:3746
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81833738)
Location: include/linux/skbuff.h:3746
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff818442b2)
Location: include/linux/skbuff.h:3746
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff818883dd)
Location: include/linux/skbuff.h:3746
Inline: True
```
```
In net/ipv6/raw.c (ffffffff818aca91)
Location: include/linux/skbuff.h:3746
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/ip_output.c (ffffffff81899202)
Location: include/linux/skbuff.h:3937
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b2ac9)
Location: include/linux/skbuff.h:3937
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff818c3bfb)
Location: include/linux/skbuff.h:3937
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff8190a98f)
Location: include/linux/skbuff.h:3937
Inline: True
```
```
In net/ipv6/raw.c (ffffffff8192f2ee)
Location: include/linux/skbuff.h:3937
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/ip_output.c (ffffffff818ed267)
Location: include/linux/skbuff.h:3947
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81907fc2)
Location: include/linux/skbuff.h:3947
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81919803)
Location: include/linux/skbuff.h:3947
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81961dc7)
Location: include/linux/skbuff.h:3947
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819881ce)
Location: include/linux/skbuff.h:3947
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/ip_output.c (ffffffff8191ac6e)
Location: include/linux/skbuff.h:4110
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819362af)
Location: include/linux/skbuff.h:4110
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff819480de)
Location: include/linux/skbuff.h:4110
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_sendmsg
```
```
In net/ipv6/ip6_output.c (ffffffff81996861)
Location: include/linux/skbuff.h:4110
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819beb0a)
Location: include/linux/skbuff.h:4110
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_sendmsg
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
In net/ipv4/ip_output.c (ffffffff8197ceb0)
Location: include/linux/skbuff.h:4217
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199a66e)
Location: include/linux/skbuff.h:4217
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff819ac46f)
Location: include/linux/skbuff.h:4217
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a02d9a)
Location: include/linux/skbuff.h:4217
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2d1b3)
Location: include/linux/skbuff.h:4217
Inline: True
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
In net/ipv4/ip_output.c (ffffffff819b3850)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d10b7)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff819e2fa9)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3996f)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a63d0b)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81a9d921)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81abe155)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81ad088c)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2f42a)
Location: include/linux/skbuff.h:4341
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5c788)
Location: include/linux/skbuff.h:4341
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81aa77da)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac9a31)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81adc89c)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81b3de77)
Location: include/linux/skbuff.h:4370
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6afcf)
Location: include/linux/skbuff.h:4370
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81a929be)
Location: include/linux/skbuff.h:4434
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab48b9)
Location: include/linux/skbuff.h:4434
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81ac78d8)
Location: include/linux/skbuff.h:4434
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b317)
Location: include/linux/skbuff.h:4434
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b592ea)
Location: include/linux/skbuff.h:4434
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81b4ddc3)
Location: include/linux/skbuff.h:4473
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b71879)
Location: include/linux/skbuff.h:4473
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81b86137)
Location: include/linux/skbuff.h:4473
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81bf1445)
Location: include/linux/skbuff.h:4473
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c20904)
Location: include/linux/skbuff.h:4473
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81cdb790)
Location: include/linux/skbuff.h:4895
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d00fdc)
Location: include/linux/skbuff.h:4895
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81d16a83)
Location: include/linux/skbuff.h:4895
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81d89bfd)
Location: include/linux/skbuff.h:4895
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbd6b4)
Location: include/linux/skbuff.h:4895
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81e9c079)
Location: include/linux/skbuff.h:4791
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec613c)
Location: include/linux/skbuff.h:4791
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81edd25e)
Location: include/linux/skbuff.h:4791
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81f57b25)
Location: include/linux/skbuff.h:4791
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8dbf3)
Location: include/linux/skbuff.h:4791
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81efab5f)
Location: include/linux/skbuff.h:4823
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f24881)
Location: include/linux/skbuff.h:4823
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81f3c4ae)
Location: include/linux/skbuff.h:4823
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff81fb758c)
Location: include/linux/skbuff.h:4823
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fee3df)
Location: include/linux/skbuff.h:4823
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff81fbeaae)
Location: include/linux/skbuff.h:4863
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe906d)
Location: include/linux/skbuff.h:4863
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff820025dd)
Location: include/linux/skbuff.h:4863
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (ffffffff82084c50)
Location: include/linux/skbuff.h:4863
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bbfa5)
Location: include/linux/skbuff.h:4863
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffff800010c63320)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c83d20)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffff800010c97d7c)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cf9b00)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d29dec)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (c0d73b54)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (c0d92f9c)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (c0da5a24)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_send_hdrinc
```
```
In net/ipv6/ip6_output.c (c0e01104)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
```
```
In net/ipv6/raw.c (c0e2da00)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (c000000000d67f68)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8f6d4)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (c000000000da8d30)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e21698)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5ac90)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffe0007cba88)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5800)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffe0007f61c6)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe0008455ce)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086a662)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff819536c0)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81970f27)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff81982e19)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d8fff)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a0339b)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff8190d1b0)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192a9f7)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff8193c8d9)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81995dbf)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c015b)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff819bde90)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819db6f7)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff819ed5e9)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a43a7f)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6de1b)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
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
In net/ipv4/ip_output.c (ffffffff819c77a0)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e5377)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/raw.c (ffffffff819f74c9)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f71f)
Location: include/linux/skbuff.h:4301
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7a447)
Location: include/linux/skbuff.h:4301
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_send_hdrinc
```
</details>
</li>
</ul>

## Differences
