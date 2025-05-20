# Function: <code>netstat_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81736570)
Location: net/core/net-sysfs.c:522
Inline: True
Direct callers:
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81736570-ffffffff81736637: netstat_show.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a2720)
Location: net/core/net-sysfs.c:539
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff817a2720-ffffffff817a27e7: netstat_show.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817d1140)
Location: net/core/net-sysfs.c:539
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff817d1140-ffffffff817d1207: netstat_show.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817f0540)
Location: net/core/net-sysfs.c:544
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff817f0540-ffffffff817f05e4: netstat_show.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186bb40)
Location: net/core/net-sysfs.c:555
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff8186bb40-ffffffff8186bbe4: netstat_show.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bc2b0)
Location: net/core/net-sysfs.c:555
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff818bc2b0-ffffffff818bc354: netstat_show.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e3410)
Location: net/core/net-sysfs.c:556
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff818e3410-ffffffff818e34b4: netstat_show.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (0)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81932ac0-ffffffff81932b7e: netstat_show.isra.0 (STB_LOCAL)
ffffffff819340d8-ffffffff819340eb: netstat_show.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81965600)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81965600-ffffffff819656ba: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a37d30)
Location: net/core/net-sysfs.c:577
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81a37d30-ffffffff81a37dda: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a39f80)
Location: net/core/net-sysfs.c:578
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81a39f80-ffffffff81a3a02a: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a21340)
Location: net/core/net-sysfs.c:618
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81a21340-ffffffff81a213e6: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81ad58c0)
Location: net/core/net-sysfs.c:667
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81ad58c0-ffffffff81ad5966: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81c55d60)
Location: net/core/net-sysfs.c:661
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81c55d60-ffffffff81c55e22: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81e0b7c0)
Location: net/core/net-sysfs.c:661
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81e0b7c0-ffffffff81e0b882: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81e7ed50)
Location: net/core/net-sysfs.c:661
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81e7ed50-ffffffff81e7ee12: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81f3fc60)
Location: net/core/net-sysfs.c:673
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81f3fc60-ffffffff81f3fd22: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c0b0e8)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffff800010c0b0e8-ffff800010c0b200: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (c0d23ad0)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
c0d23ad0-c0d23ba0: netstat_show.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf62f0)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
c000000000cf62f0-c000000000cf6400: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffe000788a80)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffe000788a80-ffffffe000788b04: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819055d0)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff819055d0-ffffffff8190568a: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bf400)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff818bf400-ffffffff818bf4ba: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81956600)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81956600-ffffffff819566ba: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81978800)
Location: net/core/net-sysfs.c:546
Inline: True
Direct callers:
  - net/core/net-sysfs.c:rx_nohandler_show
  - net/core/net-sysfs.c:tx_compressed_show
  - net/core/net-sysfs.c:rx_compressed_show
  - net/core/net-sysfs.c:tx_window_errors_show
  - net/core/net-sysfs.c:tx_heartbeat_errors_show
  - net/core/net-sysfs.c:tx_fifo_errors_show
  - net/core/net-sysfs.c:tx_carrier_errors_show
  - net/core/net-sysfs.c:tx_aborted_errors_show
  - net/core/net-sysfs.c:rx_missed_errors_show
  - net/core/net-sysfs.c:rx_fifo_errors_show
  - net/core/net-sysfs.c:rx_frame_errors_show
  - net/core/net-sysfs.c:rx_crc_errors_show
  - net/core/net-sysfs.c:rx_over_errors_show
  - net/core/net-sysfs.c:rx_length_errors_show
  - net/core/net-sysfs.c:collisions_show
  - net/core/net-sysfs.c:multicast_show
  - net/core/net-sysfs.c:tx_dropped_show
  - net/core/net-sysfs.c:rx_dropped_show
  - net/core/net-sysfs.c:tx_errors_show
  - net/core/net-sysfs.c:rx_errors_show
  - net/core/net-sysfs.c:tx_bytes_show
  - net/core/net-sysfs.c:rx_bytes_show
  - net/core/net-sysfs.c:tx_packets_show
  - net/core/net-sysfs.c:rx_packets_show
```
**Symbols:**

```
ffffffff81978800-ffffffff819788bd: netstat_show.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
