# Function: <code>rcu_read_lock_held</code>

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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/ip6_checksum.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:516
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:520
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:520
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In kernel/cgroup.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:525
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:525
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:261
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:261
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In kernel/bpf/sockmap.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In kernel/memremap.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In mm/hmm.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:266
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:266
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In kernel/bpf/sockmap.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In block/blk-sysfs.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In block/cfq-iosched.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:267
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/xfrm4_policy.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/xfrm6_policy.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:245
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:230
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/rcupdate.h:264
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:264
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/rcupdate.h:280
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:280
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
In kernel/sched/core.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xdp/xskmap.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:286
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/rcupdate.h:288
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/rcupdate.h:346
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In block/blk-cgroup-rwstat.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/rcupdate.h:322
Inline: True
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
In kernel/sched/core.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/bpf/bpf_task_storage.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/bpf/bpf_inode_storage.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In kernel/bpf/bpf_cgrp_storage.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In mm/zswap.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In mm/memremap.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In fs/aio.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In drivers/pci/p2pdma.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/gro.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ping.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/gre_offload.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv4/xfrm4_protocol.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/ioam6.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/xfrm6_protocol.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/mptcp/subflow.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
```
```
In net/mctp/route.c (0)
Location: include/linux/rcupdate.h:323
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
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
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/vxlan.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_tunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_udp_tunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
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
In kernel/sched/fair.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/helpers.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In kernel/bpf/stackmap.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/bio.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In drivers/net/loopback.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/skbuff.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/flow_dissector.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/dev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/neighbour.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/filter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/lwt_bpf.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/core/sock_map.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_fragment.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_forward.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/tcp_minisocks.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/udp_offload.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/ipmr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv4/xfrm4_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6_input.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ndisc.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/udp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/raw.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/icmp.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/inet6_connection_sock.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/ip6mr.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/xfrm6_output.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/netfilter.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/ipv6/output_core.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
```
In net/l3mdev/l3mdev.c (0)
Location: include/linux/rcupdate.h:231
Inline: True
```
</details>
</li>
</ul>

## Differences
