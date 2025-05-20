# Function: <code>__nf_ct_ext_find</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f4d70)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (ffffffff81926c40)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (ffffffff819fabd0)
Location: include/net/netfilter/nf_conntrack_extend.h:61
Inline: True
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
In net/core/flow_dissector.c (ffffffff819fa7e0)
Location: include/net/netfilter/nf_conntrack_extend.h:61
Inline: True
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
In net/core/flow_dissector.c (ffffffff819e09ca)
Location: include/net/netfilter/nf_conntrack_extend.h:61
Inline: True
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
In net/core/flow_dissector.c (ffffffff81a90d3e)
Location: include/net/netfilter/nf_conntrack_extend.h:61
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc2fb8)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (c0cde2f0)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (c000000000c9d080)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (ffffffe00074fd28)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (ffffffff818c6c40)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (ffffffff81880b80)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
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
In net/core/flow_dissector.c (ffffffff81917c40)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199dd9d)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_ct_kill_acct
  - net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_alter_reply
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1a19)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
  - net/netfilter/nf_conntrack_standalone.c:seq_print_acct
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2052)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:exp_seq_show
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_expect_related_report
  - net/netfilter/nf_conntrack_expect.c:nf_ct_remove_expectations
  - net/netfilter/nf_conntrack_expect.c:nf_ct_unlink_expect_report
```
```
In net/netfilter/nf_conntrack_helper.c (ffffffff819a3151)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_helper.c:expect_iter_me
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_log
  - net/netfilter/nf_conntrack_helper.c:nf_ct_helper_destroy
  - net/netfilter/nf_conntrack_helper.c:unhelp
  - net/netfilter/nf_conntrack_helper.c:__nf_ct_try_assign_helper
  - net/netfilter/nf_conntrack_helper.c:__nf_ct_try_assign_helper
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a48b0)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:nf_confirm
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a63b2)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a727a)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a77fc)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmp_packet
```
```
In net/netfilter/nf_conntrack_seqadj.c (ffffffff819a7fad)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_offset
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seq_adjust
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seqadj_set
  - net/netfilter/nf_conntrack_seqadj.c:nf_ct_seqadj_init
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a882c)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_packet
```
```
In net/netfilter/nf_conntrack_timeout.c (ffffffff819a8b18)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_timeout.c:nf_ct_destroy_timeout
  - net/netfilter/nf_conntrack_timeout.c:untimeout
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a944e)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_expect_event_report
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_deliver_cached_events
  - net/netfilter/nf_conntrack_ecache.c:nf_conntrack_eventmask_report
  - net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list
```
```
In net/netfilter/nf_conntrack_labels.c (ffffffff819a95ad)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_labels.c:nf_connlabels_replace
  - net/netfilter/nf_conntrack_labels.c:nf_connlabels_replace
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9d5d)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aafb8)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819abb45)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_destroy
  - net/netfilter/nf_conntrack_proto_gre.c:nf_ct_gre_keymap_add
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ac9e1)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:expect_iter_name
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_ct_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_exp_dump_expect
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_synproxy
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_change_helper
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_conntrack_event
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_synproxy
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_ct_seq_adj
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_labels
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_timestamp
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_acct
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_helpinfo
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
In net/core/flow_dissector.c (ffffffff81938e50)
Location: include/net/netfilter/nf_conntrack_extend.h:62
Inline: True
```
</details>
</li>
</ul>

## Differences
