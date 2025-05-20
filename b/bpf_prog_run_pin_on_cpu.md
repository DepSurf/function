# Function: <code>bpf_prog_run_pin_on_cpu</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a55b1)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In drivers/net/tun.c (ffffffff8188e751)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff819fb4d5)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81a3ccd8)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/packet/af_packet.c (ffffffff81b8b848)
Location: include/linux/filter.h:591
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
In kernel/seccomp.c (ffffffff811a3915)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In drivers/net/tun.c (ffffffff8189d0b1)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff819fb0ce)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81a3f672)
Location: include/linux/filter.h:591
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/packet/af_packet.c (ffffffff81b9acb7)
Location: include/linux/filter.h:591
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
In kernel/seccomp.c (ffffffff811a4537)
Location: include/linux/filter.h:633
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In drivers/net/tun.c (ffffffff8187f8e1)
Location: include/linux/filter.h:633
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff819e12f3)
Location: include/linux/filter.h:633
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81a4e603)
Location: include/linux/filter.h:633
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/packet/af_packet.c (ffffffff81b8a6bf)
Location: include/linux/filter.h:633
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
In kernel/seccomp.c (ffffffff811cdd87)
Location: include/linux/filter.h:643
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In drivers/net/tun.c (ffffffff81910a66)
Location: include/linux/filter.h:643
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff81a91733)
Location: include/linux/filter.h:643
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81b07343)
Location: include/linux/filter.h:643
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81b2bf36)
Location: include/linux/filter.h:643
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
```
In net/packet/af_packet.c (ffffffff81c567cf)
Location: include/linux/filter.h:643
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
In kernel/seccomp.c (ffffffff81201ca7)
Location: include/linux/filter.h:646
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_run_filters
```
```
In drivers/net/tun.c (ffffffff81a6083d)
Location: include/linux/filter.h:646
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff81c078c7)
Location: include/linux/filter.h:646
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81c8bde0)
Location: include/linux/filter.h:646
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81cb656b)
Location: include/linux/filter.h:646
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
```
In net/packet/af_packet.c (ffffffff81df5b55)
Location: include/linux/filter.h:646
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
In kernel/seccomp.c (ffffffff81249fe0)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In drivers/net/tun.c (ffffffff81becdfc)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff81db7352)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81e48345)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81e74a4b)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
```
In net/packet/af_packet.c (ffffffff81fca0d5)
Location: include/linux/filter.h:618
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
In kernel/seccomp.c (ffffffff812612cf)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In drivers/net/tun.c (ffffffff81c452fb)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff81e27a12)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81ea3b0a)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81ed081b)
Location: include/linux/filter.h:618
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
```
In net/packet/af_packet.c (ffffffff8202add8)
Location: include/linux/filter.h:618
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
In kernel/seccomp.c (ffffffff8127b4cf)
Location: include/linux/filter.h:669
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In drivers/net/tun.c (ffffffff81cfac2d)
Location: include/linux/filter.h:669
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In net/core/flow_dissector.c (ffffffff81ee59c2)
Location: include/linux/filter.h:669
Inline: True
Inline callers:
  - net/core/flow_dissector.c:bpf_flow_dissect
```
```
In net/core/skmsg.c (ffffffff81f6640a)
Location: include/linux/filter.h:669
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
  - net/core/skmsg.c:sk_psock_msg_verdict
```
```
In net/bpf/test_run.c (ffffffff81f9417b)
Location: include/linux/filter.h:669
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_syscall
```
```
In net/packet/af_packet.c (ffffffff820fa8d4)
Location: include/linux/filter.h:669
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
