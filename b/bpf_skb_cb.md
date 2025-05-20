# Function: <code>bpf_skb_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (0)
Location: include/linux/filter.h:387
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/filter.h:387
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/filter.h:387
Inline: True
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
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:457
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/filter.h:457
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/filter.h:457
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/filter.h:457
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/filter.h:457
Inline: True
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
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:510
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/filter.h:510
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/filter.h:510
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/filter.h:510
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/filter.h:510
Inline: True
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
In kernel/bpf/cgroup.c (0)
Location: include/linux/filter.h:515
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/filter.h:515
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/filter.h:515
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/filter.h:515
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/linux/filter.h:515
Inline: True
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
In kernel/bpf/cgroup.c (ffffffff811d1bac)
Location: include/linux/filter.h:555
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff8173d576)
Location: include/linux/filter.h:555
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/filter.c (ffffffff818b2c6e)
Location: include/linux/filter.h:555
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff818b9e26)
Location: include/linux/filter.h:555
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818c7eb7)
Location: include/linux/filter.h:555
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819a8f3d)
Location: include/linux/filter.h:555
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff819b281f)
Location: include/linux/filter.h:555
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff811e1902)
Location: include/linux/filter.h:575
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff81761034)
Location: include/linux/filter.h:575
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/filter.c (ffffffff818d5b97)
Location: include/linux/filter.h:575
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff818e0b8d)
Location: include/linux/filter.h:575
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818f1011)
Location: include/linux/filter.h:575
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819dfef2)
Location: include/linux/filter.h:575
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff819e978c)
Location: include/linux/filter.h:575
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff811f8b66)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff8179ecaf)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81923335)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff8192f230)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff819429d1)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eb00)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81a57ca5)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff81205b96)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff817c33f7)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff8195555d)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff819614a0)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81977921)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a857a0)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81a9027f)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff8122c506)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In drivers/net/tun.c (ffffffff8188e746)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81a28096)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81a349c6)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/lwt_bpf.c (ffffffff81a4c5a6)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f736)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff81b8b83d)
Location: include/linux/filter.h:659
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff81234936)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In drivers/net/tun.c (ffffffff8189d0a6)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81a28b26)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81a36d06)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/lwt_bpf.c (ffffffff81a52226)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/seg6_local.c (ffffffff81b8e6e6)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff81b9aca9)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff81239a06)
Location: include/linux/filter.h:711
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff8187f8d6)
Location: include/linux/filter.h:711
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81a1411a)
Location: include/linux/filter.h:711
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a1deec)
Location: include/linux/filter.h:711
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a37d90)
Location: include/linux/filter.h:711
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0ed)
Location: include/linux/filter.h:711
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81b8a6b1)
Location: include/linux/filter.h:711
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff812740f1)
Location: include/linux/filter.h:722
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff81910a58)
Location: include/linux/filter.h:722
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81ac59ea)
Location: include/linux/filter.h:722
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad197c)
Location: include/linux/filter.h:722
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81aedba0)
Location: include/linux/filter.h:722
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a93d)
Location: include/linux/filter.h:722
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81c567c1)
Location: include/linux/filter.h:722
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff812c1df6)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In drivers/net/tun.c (ffffffff81a6082f)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81c3c876)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81c4f246)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/lwt_bpf.c (ffffffff81c706f6)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/seg6_local.c (ffffffff81de7ee6)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff81df5b47)
Location: include/linux/filter.h:725
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff813267b6)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In drivers/net/tun.c (ffffffff81becdee)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81df4236)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e043d6)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/lwt_bpf.c (ffffffff81e286e6)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb166)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff81fca0c7)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff81356b06)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In drivers/net/tun.c (ffffffff81c452ef)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81e65e46)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81e76c26)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/lwt_bpf.c (ffffffff81e9dd06)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/seg6_local.c (ffffffff8201b826)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff8202adca)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff8137f636)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__bpf_prog_run_save_cb
```
```
In drivers/net/tun.c (ffffffff81cfac22)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81f24ff6)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_prog_run_save_cb
```
```
In net/core/sock_reuseport.c (ffffffff81f36be6)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:__bpf_prog_run_save_cb
```
```
In net/core/lwt_bpf.c (ffffffff81f60486)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:__bpf_prog_run_save_cb
```
```
In net/ipv6/seg6_local.c (ffffffff820ea7e6)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:__bpf_prog_run_save_cb
```
```
In net/packet/af_packet.c (ffffffff820fa8c6)
Location: include/linux/filter.h:748
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffff80001028eb0c)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffff8000109dee68)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffff800010c02058)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffff800010c04d20)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffff800010c1ecf0)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d5183c)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffff800010d5dab4)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (c04bddf4)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (c0ac2a50)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (c0d10458)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e1e8)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (c0d3606c)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (c0e523dc)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (c0e5c5e4)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (c00000000033b4b8)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (c000000000aa0798)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (c000000000cdce10)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c000000000ceeeec)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (c000000000d0fc34)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e89aa8)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (c000000000e9668c)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffe0001c1d0e)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffe0006280ca)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffe000778592)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffe00078397e)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffe000797d8e)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe000889a22)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffe000893870)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff811fe1b6)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff81787ec7)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff818f552d)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81901470)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81917791)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a24e30)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81a2f90f)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff811f0f06)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff81767817)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff818af35d)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff818bb2a0)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818d1541)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e1bf0)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff819ecaff)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff811fbf86)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff817b8277)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff8194655d)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff819524a0)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81968921)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f8b0)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81a9b4bf)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
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
In kernel/bpf/cgroup.c (ffffffff8120ab8a)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In drivers/net/tun.c (ffffffff817d0561)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/filter.c (ffffffff81967e57)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81973ef2)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff8198acdf)
Location: include/linux/filter.h:631
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c640)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
```
In net/packet/af_packet.c (ffffffff81aa5cae)
Location: include/linux/filter.h:631
Inline: True
Inline callers:
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_rcv
  - net/packet/af_packet.c:packet_rcv_fanout
```
</details>
</li>
</ul>

## Differences
