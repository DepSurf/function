# Function: <code>tcp_receive_window</code>

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
In net/ipv4/tcp.c (ffffffff81765fa7)
Location: include/net/tcp.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8177007d)
Location: include/net/tcp.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81775f78)
Location: include/net/tcp.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8177ff2b)
Location: include/net/tcp.h:688
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff817d2517)
Location: include/net/tcp.h:684
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff817de98f)
Location: include/net/tcp.h:684
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff817e2f49)
Location: include/net/tcp.h:684
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff817ed419)
Location: include/net/tcp.h:684
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81802307)
Location: include/net/tcp.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8180ed6f)
Location: include/net/tcp.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818135f9)
Location: include/net/tcp.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8181dd29)
Location: include/net/tcp.h:682
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff8182246a)
Location: include/net/tcp.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8182ec91)
Location: include/net/tcp.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81833801)
Location: include/net/tcp.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8183e490)
Location: include/net/tcp.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff818a156a)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff818adcc1)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff818b2b91)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff818bdcc0)
Location: include/net/tcp.h:666
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff818f6044)
Location: include/net/tcp.h:676
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819031e9)
Location: include/net/tcp.h:676
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81908087)
Location: include/net/tcp.h:676
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81912744)
Location: include/net/tcp.h:676
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81923c04)
Location: include/net/tcp.h:703
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81931339)
Location: include/net/tcp.h:703
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8193636c)
Location: include/net/tcp.h:703
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81940f14)
Location: include/net/tcp.h:703
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff8198657e)
Location: include/net/tcp.h:704
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81994a30)
Location: include/net/tcp.h:704
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8199a738)
Location: include/net/tcp.h:704
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819a5538)
Location: include/net/tcp.h:704
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff819bccee)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819cb580)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819d1181)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819dc227)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81aa7bae)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81ab854b)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81abe221)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac9387)
Location: include/net/tcp.h:730
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81ab5a30)
Location: include/net/tcp.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81ac3777)
Location: include/net/tcp.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81ac9aee)
Location: include/net/tcp.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ad52d7)
Location: include/net/tcp.h:736
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81aa0c10)
Location: include/net/tcp.h:741
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81aae898)
Location: include/net/tcp.h:741
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81ab4973)
Location: include/net/tcp.h:741
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ac0354)
Location: include/net/tcp.h:741
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81b5ca60)
Location: include/net/tcp.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81b6b578)
Location: include/net/tcp.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81b71939)
Location: include/net/tcp.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81b7f2e8)
Location: include/net/tcp.h:734
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81ceb3f4)
Location: include/net/tcp.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81cfa6d2)
Location: include/net/tcp.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81d0109f)
Location: include/net/tcp.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81d0ec92)
Location: include/net/tcp.h:748
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81eaad66)
Location: include/net/tcp.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81ebf212)
Location: include/net/tcp.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81ec61ff)
Location: include/net/tcp.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ed4782)
Location: include/net/tcp.h:761
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81f0d406)
Location: include/net/tcp.h:756
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81f1d6d2)
Location: include/net/tcp.h:756
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81f24941)
Location: include/net/tcp.h:756
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81f325dd)
Location: include/net/tcp.h:756
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff81fd1506)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp.c:__tcp_cleanup_rbuf
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81fe1d7e)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9133)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff85be)
Location: include/net/tcp.h:771
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffff800010c6ef98)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffff800010c7e174)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffff800010c83dac)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffff800010c9015c)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (c0d7db50)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (c0d8d14c)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (c0d93034)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (c0d9e380)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (c000000000d75264)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (c000000000d882b0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (c000000000d8f788)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (c000000000d9e138)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffe0007d3d22)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0584)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffe0007e58d8)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffe0007ef61c)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff8195cb5e)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff8196b3f0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81970ff1)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff8197c097)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff8191664e)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff81924ee0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff8192aac1)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81935b57)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff819c732e)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819d5bc0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819db7c1)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819e6867)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
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
In net/ipv4/tcp.c (ffffffff819d0e7e)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_cleanup_rbuf
```
```
In net/ipv4/tcp_input.c (ffffffff819df7c0)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_validate_incoming
  - net/ipv4/tcp_input.c:tcp_data_queue
  - net/ipv4/tcp_input.c:tcp_data_queue
```
```
In net/ipv4/tcp_output.c (ffffffff819e5441)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_minisocks.c (ffffffff819f0527)
Location: include/net/tcp.h:725
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_time_wait
```
</details>
</li>
</ul>

## Differences
