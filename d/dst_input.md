# Function: <code>dst_input</code>

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
In net/ipv4/ip_input.c (ffffffff817587ac)
Location: include/net/dst.h:496
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff817afdb2)
Location: include/net/dst.h:496
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_input.c (ffffffff817c852d)
Location: include/net/dst.h:496
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff817f3a33)
Location: include/net/dst.h:496
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv4/ip_input.c (ffffffff817c4b12)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff8181ce22)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_input.c (ffffffff818356b4)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81862953)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
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
In net/ipv4/ip_input.c (ffffffff817f4632)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff8184e6f2)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_input.c (ffffffff818671e4)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff818949f7)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a45e9)
Location: include/net/dst.h:505
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
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
In net/ipv4/ip_input.c (ffffffff81814a6a)
Location: include/net/dst.h:475
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81872150)
Location: include/net/dst.h:475
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/ipv6/ip6_input.c (ffffffff8188b95f)
Location: include/net/dst.h:475
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff818baff1)
Location: include/net/dst.h:475
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818cad40)
Location: include/net/dst.h:475
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
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
In net/ipv4/ip_input.c (ffffffff81893c0d)
Location: include/net/dst.h:464
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff818f2995)
Location: include/net/dst.h:464
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff8190cc32)
Location: include/net/dst.h:464
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff8193e001)
Location: include/net/dst.h:464
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194e680)
Location: include/net/dst.h:464
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff8194fa02)
Location: include/net/dst.h:464
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/ipv4/ip_input.c (ffffffff818e7eb8)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff819492d5)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81963fdb)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81996f32)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a796b)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819a9004)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/ipv4/ip_input.c (ffffffff81914c85)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197af85)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff819997b7)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff819cd826)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de4c8)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819dff84)
Location: include/net/dst.h:448
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81942c02)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff81977170)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4475)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81a05632)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c739)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4d031)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a4ebe0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81977b73)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff819adb00)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b485)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81a3b990)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81a733b9)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a83c01)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a85880)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81a4d2f4)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff81a97910)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c545)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81b31a05)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d827)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e9de)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b8078a)
Location: include/net/dst.h:447
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81a52fb4)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff81aa1870)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1a865)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81b40605)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c2d7)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d9e0)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b9001f)
Location: include/net/dst.h:445
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81a387c4)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff81a8d415)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08565)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e6dd)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81b6adb9)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c88e)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f1d4)
Location: include/net/dst.h:456
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81aee5dc)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81b485d5)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb475)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81bf49f8)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81c32c19)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c477f3)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81c4aa33)
Location: include/net/dst.h:458
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81c714d0)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81cd5985)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d60e65)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d7d4)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81dd040f)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6bc5)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81dea2f5)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81e29590)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81e95e05)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b725)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b8e4)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81fa179f)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9a2d)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdbb5)
Location: include/net/dst.h:452
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81e9ebc0)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81ef4645)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b3a5)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81fbb6a2)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff82002011)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8201a163)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff8201ebd5)
Location: include/net/dst.h:466
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
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
In net/core/lwt_bpf.c (ffffffff81f61330)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_input_reroute
```
```
In net/ipv4/ip_input.c (ffffffff81fb85c5)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff82052aa5)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff82088ae1)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ipv6_rcv
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff820d0e11)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e9130)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input_core
```
```
In net/ipv6/seg6_local.c (ffffffff820edd05)
Location: include/net/dst.h:459
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
  - net/ipv6/seg6_local.c:end_flv8986_core
  - net/ipv6/seg6_local.c:input_action_end_x_core
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
In net/core/lwt_bpf.c (ffff800010c1f148)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffff800010c5df78)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd76d8)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffff800010cfccd0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffff800010d3be2c)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f96c)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffff800010d51930)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (c0d36398)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (c0d6d2ec)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (c0de1200)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (c0e04050)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (c0e3ebb4)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (c0e506c0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c0e5249c)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_b6_encap
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (c000000000d100f4)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (c000000000d605f0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (c000000000df74ec)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (c000000000e248f0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (c000000000e6f844)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e870a4)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (c000000000e89bf4)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffe000798096)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffe0007c6788)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827dfe)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffe000847328)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffe0008788b8)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe0008880fc)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffe000889aa8)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff819179e3)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff8194d970)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bab15)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff819db020)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81a12a49)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a23291)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a24f10)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff818d1793)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff81907460)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977905)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81997de0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff819cf809)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819e0051)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff819e1cd0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff81968b73)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff819b8140)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a25595)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81a45aa0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81a7d4c9)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8dd11)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f990)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
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
In net/core/lwt_bpf.c (ffffffff8198af53)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
```
In net/ipv4/ip_input.c (ffffffff819c19a0)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv_finish
  - net/ipv4/ip_input.c:ip_rcv_finish
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30a15)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_rcv_encap_finish2
```
```
In net/ipv6/ip6_input.c (ffffffff81a51770)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv_finish
  - net/ipv6/ip6_input.c:ip6_rcv_finish
```
```
In net/ipv6/exthdrs.c (ffffffff81a89d19)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9aa25)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_input
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c751)
Location: include/net/dst.h:440
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
  - net/ipv6/seg6_local.c:input_action_end_dt6
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx6
  - net/ipv6/seg6_local.c:input_action_end_t
  - net/ipv6/seg6_local.c:input_action_end_x
  - net/ipv6/seg6_local.c:input_action_end
```
</details>
</li>
</ul>

## Differences
