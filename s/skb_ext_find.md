# Function: <code>skb_ext_find</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/xfrm.c (ffffffff81433b45)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff818d59e5)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff818f8157)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff8190de59)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffff81917623)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/udp.c (ffffffff8194b009)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/icmp.c (ffffffff81953c20)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff8197b085)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff819832d9)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a639)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b563)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198be45)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ce73)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff8199778f)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff819c142f)
Location: include/linux/skbuff.h:3980
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d8a85)
Location: include/linux/skbuff.h:3980
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
In security/selinux/xfrm.c (ffffffff814615d5)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff81923185)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff819578ac)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff8196fa39)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffff81979575)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/udp.c (ffffffff819af669)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_set_dev_scratch
```
```
In net/ipv4/icmp.c (ffffffff819b8511)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff819e4584)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecef3)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5236)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6a68)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff819f73c5)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819f86de)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a037c5)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81a30201)
Location: include/linux/skbuff.h:4087
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a472d6)
Location: include/linux/skbuff.h:4087
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
In security/selinux/xfrm.c (ffffffff8147b385)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff819553b5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff8198dd4c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff819a63a9)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffff819afe8a)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffffffff819ef211)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a1b594)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23f03)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2bee6)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d6d0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a2e015)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f33e)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a395)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81a66d51)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7de86)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (ffffffff814d0935)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff81a27fc5)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff81a657bf)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81a6be33)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
```
In net/netfilter/nf_queue.c (ffffffff81a8f881)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_forward.c (ffffffff81a99daf)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81ab210f)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ac03b6)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
```
```
In net/ipv4/icmp.c (ffffffff81add163)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b0c634)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15f31)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e394)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fe86)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b20f45)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b21df5)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81b2fb18)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81b5f7de)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b789d4)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff81baa6c1)
Location: include/linux/skbuff.h:4199
Inline: True
```
```
In net/mptcp/subflow.c (ffffffff81baf130)
Location: include/linux/skbuff.h:4199
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bb0a81)
Location: include/linux/skbuff.h:4199
Inline: True
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
In security/selinux/xfrm.c (ffffffff814ede45)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff81a2888b)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff81a6d8d0)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81a746c1)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
```
In net/netfilter/nf_queue.c (ffffffff81a99871)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_forward.c (ffffffff81aa3d18)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81abd0d3)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81acbe16)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/icmp.c (ffffffff81ae9eb3)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b1a954)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b243ab)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2cc64)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e796)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2f915)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b307e4)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e5b4)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81b6df7e)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b87944)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff81bba0a6)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
```
```
In net/mptcp/subflow.c (ffffffff81bc1d66)
Location: include/linux/skbuff.h:4228
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bc4900)
Location: include/linux/skbuff.h:4228
Inline: True
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
In security/selinux/xfrm.c (ffffffff814f4bb5)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/dev.c (ffffffff819e76cf)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/core/filter.c (ffffffff81a0fc6b)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff81a56036)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81a5d246)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify_ingress
```
```
In net/netfilter/nf_queue.c (ffffffff81a84b81)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_forward.c (ffffffff81a8ed84)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81aa7f1f)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab7055)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/icmp.c (ffffffff81ad5602)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81b08604)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11fdb)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1a8a4)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c4a3)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b1d615)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e514)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ce27)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81b5c348)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b765f4)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff81ba9456)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
```
```
In net/mptcp/subflow.c (ffffffff81bb26c6)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bb5005)
Location: include/linux/skbuff.h:4292
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_get_reset_option
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/xfrm.c (ffffffff8154f595)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/dev.c (ffffffff81a98502)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/core/filter.c (ffffffff81ac55e1)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff81b0edef)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81b16894)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netfilter/nf_queue.c (ffffffff81b3f1af)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_forward.c (ffffffff81b4a12c)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81b6431e)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b74245)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/icmp.c (ffffffff81b9442c)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81bcb514)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd5cf7)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdeec2)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be13f7)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81be249e)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81be3004)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81bf2f81)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81c23a64)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c41084)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff81c78a37)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_update_data_checksum
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
```
```
In net/mptcp/subflow.c (ffffffff81c80ba5)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81c83845)
Location: include/linux/skbuff.h:4330
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
```
**Symbols:**

```
ffffffff81bde2c0-ffffffff81bde2dd: skb_ext_find.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/xfrm.c (ffffffff815e8885)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff81c40e42)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/core/gro.c (ffffffff81c53c87)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/sched/sch_generic.c (ffffffff81c960a0)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81c9dfa2)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netfilter/nf_queue.c (ffffffff81ccb8ef)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_forward.c (ffffffff81cd76b5)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81cf3294)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d0371b)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/icmp.c (ffffffff81d25cb4)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81d60fc7)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c5b1)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81d75c2f)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7832f)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81d79593)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a205)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81d8bb06)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81dc0993)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf817)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff81e1efd6)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e265f8)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29815)
Location: include/linux/skbuff.h:4752
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81d750a0-ffffffff81d750c5: skb_ext_find.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/xfrm.c (ffffffff816980b5)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff81df6562)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/core/gro.c (ffffffff81e0941e)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/sched/sch_generic.c (ffffffff81e51c80)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81e5a6b2)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netfilter/nf_queue.c (ffffffff81e8b73f)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81e95417)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81e977e2)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81eb78c4)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec865b)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ecdddc)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81edcb2c)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81ee065c)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81eed42b)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f2b8b7)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f3793c)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4236f)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44ba8)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81f46023)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47075)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81f59aba)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81f5a977)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81f87aac)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8cadc)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81f9111b)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9a62c)
Location: include/linux/skbuff.h:4648
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb1ae7)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff81ff5b8f)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffdd28)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff820018f5)
Location: include/linux/skbuff.h:4648
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81f41730-ffffffff81f41755: skb_ext_find.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/xfrm.c (ffffffff816d0585)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/flow_dissector.c (ffffffff81e26c12)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/core/filter.c (ffffffff81e67e72)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/core/gro.c (ffffffff81e7ba87)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/sched/sch_generic.c (ffffffff81ead4bc)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81eb62a9)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netfilter/nf_queue.c (ffffffff81ee9789)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81ef3be9)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6012)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81f15fa5)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f2717b)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2cbfe)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81f3bd4e)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv4/udp.c (ffffffff81f3f90e)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff81f4cdeb)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81f8b707)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f97354)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81fa1b8f)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa43de)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81fa577c)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6a95)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff81fb976c)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff81fba6d9)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv6/udp.c (ffffffff81fe7f3e)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fed28e)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81ff19de)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffb03e)
Location: include/linux/skbuff.h:4680
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820121c7)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff82071c71)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff82079f08)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207ddb5)
Location: include/linux/skbuff.h:4680
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_dss
```
**Symbols:**

```
ffffffff81fa0fd0-ffffffff81fa0ff5: skb_ext_find.constprop.0 (STB_LOCAL)
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
In security/selinux/xfrm.c (ffffffff8170cba5)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/flow_dissector.c (ffffffff81ee4ba3)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/core/filter.c (ffffffff81f27042)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/core/gro.c (ffffffff81f3bd16)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/sched/sch_generic.c (ffffffff81f6ff59)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/sched/sch_generic.c:dequeue_skb
```
```
In net/sched/cls_api.c (ffffffff81f78fa9)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_classify
```
```
In net/netfilter/nf_queue.c (ffffffff81fad643)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:__nf_queue
  - net/netfilter/nf_queue.c:__nf_queue
```
```
In net/ipv4/ip_input.c (ffffffff81fb7b79)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv4/ip_forward.c (ffffffff81fb9fa2)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/tcp_input.c (ffffffff81fda2af)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_try_coalesce
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
  - net/ipv4/tcp_input.c:tcp_shift_skb_data
```
```
In net/ipv4/tcp_output.c (ffffffff81febb6b)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_retrans_try_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff6338)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
  - net/ipv4/tcp_ipv4.c:tcp_add_backlog
```
```
In net/ipv4/raw.c (ffffffff82001e6e)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv4/udp.c (ffffffff8200575e)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv4/icmp.c (ffffffff82012efb)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff82053007)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff820646cb)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff8206eeb0)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff82071755)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff82072acc)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
```
```
In net/xfrm/xfrm_device.c (ffffffff82073d85)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_beet_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffff82086cb1)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/ip6_input.c (ffffffff82087b09)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv6/udp.c (ffffffff820b617e)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bae8e)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff820bf5dd)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820c8a4e)
Location: include/linux/skbuff.h:4720
Inline: True
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e1337)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/mptcp/protocol.c (ffffffff82145e11)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214f368)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82152ff5)
Location: include/linux/skbuff.h:4720
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_dss
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
In security/selinux/xfrm.c (ffff80001056bcac)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffff800010bf7150)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffff800010c39338)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffff800010c55ba0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffff800010c605e0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffff800010ca505c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffff800010cd781c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce1158)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffff800010cea9ac)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffff800010cec124)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffff800010cecfec)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffff800010cee464)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffff800010cfb388)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffff800010d2ccc8)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffff800010d4925c)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (c071f5d8)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (c0d101ec)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (c0d4b7b0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (c0d655b0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (c0d6ff18)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (c0db1964)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (c0de133c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (c0dea4a4)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (c0df29c0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (c0df4028)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (c0df4db4)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c0df62f8)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (c0e01fe0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (c0e30d24)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (c0e4a620)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (c0000000006cfc5c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (c000000000cdcb60)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (c000000000d320a4)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (c000000000d563c0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (c000000000d635c0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (c000000000db8d90)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (c000000000df76c8)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (c000000000e03688)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (c000000000e0e620)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (c000000000e10144)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (c000000000e11378)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (c000000000e130c0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (c000000000e22960)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (c000000000e5e794)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e760)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (ffffffe0003c091e)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffe000778fa4)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffe0007aa810)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffe0007c0012)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffe0007c879c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffffffe0008009a0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffe000827efe)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fcc4)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffe000838516)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffe000839960)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a536)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b6a8)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
  - net/xfrm/xfrm_device.c:__xfrm_mode_tunnel_prep
```
```
In net/ipv6/ip6_output.c (ffffffe000845e6c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffe00086cf2c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffe00088275c)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (ffffffff81473965)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff818f5385)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff8192dbbc)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff81946219)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffff8194fcfa)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffffffff8198efb1)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff819bac24)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c3593)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff819cb576)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccd60)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff819cd6a5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce9ce)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819d9a25)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81a063e1)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d516)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (ffffffff81464385)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff818af1b5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff818e76bc)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff818ffd09)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffff819097ea)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffffffff81948a71)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81977a14)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980383)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81988366)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81989b50)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198a495)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b790)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff819967e5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff819c31a1)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da2d6)
Location: include/linux/skbuff.h:4159
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
In security/selinux/xfrm.c (ffffffff8146fa05)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff819463b5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff8197ed4c)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff819973a9)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/netfilter/nfnetlink_queue.c (ffffffff8199a980)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
  - net/netfilter/nfnetlink_queue.c:nfqnl_enqueue_packet
```
```
In net/netfilter/nfnetlink_log.c (ffffffff8199be27)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nfnetlink_log.c:__build_packet_message
```
```
In net/ipv4/ip_forward.c (ffffffff819ba4ca)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffffffff819f9851)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/netfilter/nf_defrag_ipv4.c (ffffffff81a20c32)
Location: include/linux/skbuff.h:4159
Inline: True
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a256a4)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2e013)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35ff6)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81a377e0)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a38125)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3944e)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a444a5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81a70e61)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a87f96)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
```
In net/ipv6/netfilter/nf_defrag_ipv6_hooks.c (ffffffff81a90807)
Location: include/linux/skbuff.h:4159
Inline: True
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
In security/selinux/xfrm.c (ffffffff81487275)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_sock_rcv_skb
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
  - security/selinux/xfrm.c:selinux_xfrm_skb_sid_ingress
```
```
In net/core/filter.c (ffffffff81967ca5)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_get_xfrm_state
```
```
In net/sched/sch_generic.c (ffffffff819a12d3)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/sched/sch_generic.c:__qdisc_run
```
```
In net/netfilter/nf_queue.c (ffffffff819ba089)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_get_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
  - net/netfilter/nf_queue.c:nf_queue_entry_release_refs
```
```
In net/ipv4/ip_forward.c (ffffffff819c3dba)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/icmp.c (ffffffff81a03b41)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_rcv
```
```
In net/ipv4/xfrm4_input.c (ffffffff81a30b26)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv4/xfrm4_input.c:xfrm4_transport_finish
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39808)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41964)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:secpath_set
```
```
In net/xfrm/xfrm_output.c (ffffffff81a43190)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a44185)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44e7e)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
```
In net/ipv6/ip6_output.c (ffffffff81a50167)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_forward
```
```
In net/ipv6/icmp.c (ffffffff81a7d471)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_rcv
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94bb6)
Location: include/linux/skbuff.h:4159
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_transport_finish
```
</details>
</li>
</ul>

## Differences
