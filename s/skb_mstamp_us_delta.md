# Function: <code>skb_mstamp_us_delta</code>

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
In net/ipv4/tcp_input.c (ffffffff8176d2e9)
Location: include/linux/skbuff.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81776d76)
Location: include/linux/skbuff.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_recovery.c (ffffffff81782f8d)
Location: include/linux/skbuff.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
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
In net/ipv4/tcp_input.c (ffffffff817db081)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff817e3d28)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_recovery.c (ffffffff817f0657)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
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
In net/ipv4/tcp_input.c (ffffffff8180ac79)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81814261)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_rate.c (ffffffff8182102d)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_gen
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff818213c7)
Location: include/linux/skbuff.h:538
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_mark_lost
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
