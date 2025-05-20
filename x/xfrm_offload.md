# Function: <code>xfrm_offload</code>

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
In net/ipv4/xfrm4_input.c (ffffffff8187209c)
Location: include/net/xfrm.h:1847
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e158)
Location: include/net/xfrm.h:1847
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ed21)
Location: include/net/xfrm.h:1847
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8187f5dc)
Location: include/net/xfrm.h:1847
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81880064)
Location: include/net/xfrm.h:1847
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c5a36)
Location: include/net/xfrm.h:1847
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/ipv4/xfrm4_input.c (ffffffff818f2a7c)
Location: include/net/xfrm.h:1850
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff088)
Location: include/net/xfrm.h:1850
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffe12)
Location: include/net/xfrm.h:1850
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8190070c)
Location: include/net/xfrm.h:1850
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81901174)
Location: include/net/xfrm.h:1850
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948d5c)
Location: include/net/xfrm.h:1850
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff818ccdfa)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff819493d6)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81955b6d)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819568fe)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81957213)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81957d77)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1e46)
Location: include/net/xfrm.h:1884
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff818f8157)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b085)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a639)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b563)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198be45)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ce73)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8a85)
Location: include/net/xfrm.h:1892
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff819578ac)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4584)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5236)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6a68)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff819f73c5)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819f86de)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a472d6)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff8198dd4c)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b594)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bee6)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d6d0)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a2e015)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f33e)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7de86)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81a657bf)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c634)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e394)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fe86)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b20f45)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21df5)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b789d4)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81a6d8d0)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1a954)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cc64)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e796)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2f915)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b307e4)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87944)
Location: include/net/xfrm.h:1833
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81a56036)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08604)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a8a4)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c4a3)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b1d615)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e514)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b765f4)
Location: include/net/xfrm.h:1834
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81b0edef)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb514)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdeec2)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be13f7)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81be249e)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3004)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41084)
Location: include/net/xfrm.h:1856
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81c960a0)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d60fc7)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75c2f)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7832f)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81d79593)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a205)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf817)
Location: include/net/xfrm.h:1859
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81e51c80)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_input.c (ffffffff81e95417)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81e977e2)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdddc)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edcb2c)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee065c)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eeb7fc)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b8b7)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4236f)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44ba8)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81f46023)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47075)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81f55257)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81f5a977)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f87aac)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8cadc)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81f8f7ec)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a62c)
Location: include/net/xfrm.h:1114
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1ae7)
Location: include/net/xfrm.h:1114
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81ead4bc)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_input.c (ffffffff81ef3be9)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6012)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2cbfe)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3bd4e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f90e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4b12e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b707)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1b8f)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa43de)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81fa577c)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6a95)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81fb4ca9)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff81fba6d9)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe7f3e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fed28e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81ff001e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb03e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820121c7)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff81f6ff59)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/ipv4/ip_input.c (ffffffff81fb7b79)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9fa2)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff244e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/raw.c (ffffffff82001e6e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8200575e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff8201123e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff82053007)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff8206eeb0)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff82071755)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff82072acc)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff82073d85)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff82082349)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/ip6_input.c (ffffffff82087b09)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b617e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bae8e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff820bdbee)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8a4e)
Location: include/net/xfrm.h:1120
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1337)
Location: include/net/xfrm.h:1120
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffff800010c39338)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd781c)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffff800010cea9ac)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010cec124)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffff800010cecfec)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffff800010cee464)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffff800010d4925c)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (c0d4b7b0)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (c0de133c)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c0df29c0)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c0df4028)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (c0df4db4)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c0df62f8)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (c0e4a620)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (c000000000d320a4)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (c000000000df76c8)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (c000000000e0e620)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e10144)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (c000000000e11378)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c000000000e130c0)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e760)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffe0007aa810)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827efe)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffe000838516)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000839960)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a536)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b6a8)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/xfrm6_input.c (ffffffe00088275c)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff8192dbbc)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bac24)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb576)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccd60)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff819cd6a5)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce9ce)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d516)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff818e76bc)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977a14)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81988366)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81989b50)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198a495)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b790)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da2d6)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff8197ed4c)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a256a4)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35ff6)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a377e0)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a38125)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3944e)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a87f96)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
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
In net/sched/sch_generic.c (ffffffff819a12d3)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30b26)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41964)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a43190)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a44185)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44e7e)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94bb6)
Location: include/net/xfrm.h:1831
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
</details>
</li>
</ul>

## Differences
