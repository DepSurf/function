# Function: <code>packet_sock_flag</code>

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
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82027884)
Location: net/packet/internal.h:158
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_xmit
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
In net/packet/af_packet.c (ffffffff820f70e4)
Location: net/packet/internal.h:158
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_seq_show
  - net/packet/af_packet.c:packet_set_ring
  - net/packet/af_packet.c:packet_notifier
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_getsockopt
  - net/packet/af_packet.c:packet_recvmsg
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_do_bind
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_snd
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:fanout_add
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_xmit
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
