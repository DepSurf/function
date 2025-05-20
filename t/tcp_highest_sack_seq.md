# Function: <code>tcp_highest_sack_seq</code>

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
In net/ipv4/tcp_input.c (ffffffff8176c40f)
Location: include/net/tcp.h:1585
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81774f10)
Location: include/net/tcp.h:1585
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
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
In net/ipv4/tcp_input.c (ffffffff817d9474)
Location: include/net/tcp.h:1600
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
```
In net/ipv4/tcp_output.c (ffffffff817e5f20)
Location: include/net/tcp.h:1600
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
In net/ipv4/tcp_input.c (ffffffff81809cac)
Location: include/net/tcp.h:1675
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
```
In net/ipv4/tcp_output.c (ffffffff818123aa)
Location: include/net/tcp.h:1675
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
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
In net/ipv4/tcp_input.c (ffffffff8182a25f)
Location: include/net/tcp.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
```
In net/ipv4/tcp_output.c (ffffffff81831cd6)
Location: include/net/tcp.h:1726
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_adjust_pcount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818acfdc)
Location: include/net/tcp.h:1690
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81902752)
Location: include/net/tcp.h:1706
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81930842)
Location: include/net/tcp.h:1778
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81993e53)
Location: include/net/tcp.h:1807
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ca9a3)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab7954)
Location: include/net/tcp.h:1867
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac2c0e)
Location: include/net/tcp.h:1881
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aadd9e)
Location: include/net/tcp.h:1885
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6a88e)
Location: include/net/tcp.h:1878
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf9a58)
Location: include/net/tcp.h:1934
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ebe568)
Location: include/net/tcp.h:1954
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1ca08)
Location: include/net/tcp.h:1967
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
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
In net/ipv4/tcp_input.c (ffffffff81fe11eb)
Location: include/net/tcp.h:2069
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_fastretrans_alert
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
  - net/ipv4/tcp_input.c:tcp_check_sack_reordering
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7d674)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d8c508)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_one
  - net/ipv4/tcp_input.c:tcp_sacktag_one
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d87458)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dfbc4)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196a813)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81924303)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4fe3)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819debc3)
Location: include/net/tcp.h:1829
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_ack
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_force_fast_retransmit
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_write_queue
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
  - net/ipv4/tcp_input.c:tcp_sacktag_walk
```
</details>
</li>
</ul>

## Differences
