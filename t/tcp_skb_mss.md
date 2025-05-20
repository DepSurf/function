# Function: <code>tcp_skb_mss</code>

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
In net/ipv4/tcp_input.c (ffffffff8176efe2)
Location: include/net/tcp.h:809
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
```
```
In net/ipv4/tcp_output.c (ffffffff81776290)
Location: include/net/tcp.h:809
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/ipv4/tcp_input.c (ffffffff817dcccd)
Location: include/net/tcp.h:815
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff817e31d8)
Location: include/net/tcp.h:815
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/ipv4/tcp_input.c (ffffffff8180cded)
Location: include/net/tcp.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81813889)
Location: include/net/tcp.h:832
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/ipv4/tcp_input.c (ffffffff8182d04d)
Location: include/net/tcp.h:884
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff81833b13)
Location: include/net/tcp.h:884
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/ipv4/tcp_input.c (ffffffff818abf3e)
Location: include/net/tcp.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
```
In net/ipv4/tcp_output.c (ffffffff818b2e35)
Location: include/net/tcp.h:886
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_transmit_skb
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
In net/ipv4/tcp_input.c (ffffffff8190146e)
Location: include/net/tcp.h:904
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81908a32)
Location: include/net/tcp.h:904
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff819172a0)
Location: include/net/tcp.h:904
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff8192f55e)
Location: include/net/tcp.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81936c9a)
Location: include/net/tcp.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81945ab0)
Location: include/net/tcp.h:942
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81992a8e)
Location: include/net/tcp.h:943
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff8199c290)
Location: include/net/tcp.h:943
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff819aa0b2)
Location: include/net/tcp.h:943
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819c95ce)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff819d2d30)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff819e0d72)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81ab57ae)
Location: include/net/tcp.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81abf9f7)
Location: include/net/tcp.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ace362)
Location: include/net/tcp.h:975
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81ac0a17)
Location: include/net/tcp.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81acb46c)
Location: include/net/tcp.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ada372)
Location: include/net/tcp.h:980
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81aab7b7)
Location: include/net/tcp.h:960
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81ab651a)
Location: include/net/tcp.h:960
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81ac53d2)
Location: include/net/tcp.h:960
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81b67bf7)
Location: include/net/tcp.h:953
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81b7351a)
Location: include/net/tcp.h:953
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81b83be2)
Location: include/net/tcp.h:953
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81cf6cfa)
Location: include/net/tcp.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81d02c6d)
Location: include/net/tcp.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d14320)
Location: include/net/tcp.h:968
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81ebb74a)
Location: include/net/tcp.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81ec7d34)
Location: include/net/tcp.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda3a0)
Location: include/net/tcp.h:981
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81f19bca)
Location: include/net/tcp.h:976
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81f26601)
Location: include/net/tcp.h:976
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f39480)
Location: include/net/tcp.h:976
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81fde39a)
Location: include/net/tcp.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81feafe1)
Location: include/net/tcp.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_trim_head
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff570)
Location: include/net/tcp.h:1013
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffff800010c7c510)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffff800010c858f8)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffff800010c94bf0)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (c0d8b470)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (c0d94b1c)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (c0da3484)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (c000000000d86060)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (c000000000d91b00)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (c000000000da54c4)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffe0007dee04)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffe0007e710c)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffe0007f3f6a)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff8196943e)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff81972ba0)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff81980be2)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff81922f2e)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff8192c670)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff8193a6a2)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819d3c0e)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff819dd370)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff819eb3b2)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff819dd7ee)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_simple_retransmit
  - net/ipv4/tcp_input.c:tcp_mark_head_lost
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_match_skb_to_sack
```
```
In net/ipv4/tcp_output.c (ffffffff819e6ff0)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:__tcp_transmit_skb
```
```
In net/ipv4/tcp_recovery.c (ffffffff819f5232)
Location: include/net/tcp.h:964
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_newreno_mark_lost
```
</details>
</li>
</ul>

## Differences
