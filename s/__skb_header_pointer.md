# Function: <code>__skb_header_pointer</code>

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
In kernel/bpf/core.c (ffffffff81172687)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff81348f33)
Location: include/linux/skbuff.h:2864
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81361e48)
Location: include/linux/skbuff.h:2864
Inline: True
```
```
In security/lsm_audit.c (ffffffff8136632a)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81711c9e)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_get_poff
```
```
In net/core/filter.c (ffffffff81732354)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ethernet/eth.c (ffffffff8174023f)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff81756037)
Location: include/linux/skbuff.h:2864
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81785c0a)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff8178e72e)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv6/raw.c (ffffffff817e703e)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff817e783b)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/exthdrs_core.c (ffffffff817ffc05)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
```
```
In net/ipv6/output_core.c (ffffffff81800822)
Location: include/linux/skbuff.h:2864
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In kernel/bpf/core.c (ffffffff8118046a)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff8137e032)
Location: include/linux/skbuff.h:3071
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81397fa7)
Location: include/linux/skbuff.h:3071
Inline: True
```
```
In security/lsm_audit.c (ffffffff8139c493)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff8177a8f2)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/filter.c (ffffffff8179d5b4)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff817ad009)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff817c2275)
Location: include/linux/skbuff.h:3071
Inline: True
```
```
In net/ipv4/raw.c (ffffffff817f3228)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff817fbd78)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv6/raw.c (ffffffff81855475)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81855c6a)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/exthdrs_core.c (ffffffff81871681)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81871f58)
Location: include/linux/skbuff.h:3071
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In kernel/bpf/core.c (ffffffff8118c2da)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff81394ac2)
Location: include/linux/skbuff.h:3123
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813aeb87)
Location: include/linux/skbuff.h:3123
Inline: True
```
```
In security/lsm_audit.c (ffffffff813b3043)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff817a7ee2)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/filter.c (ffffffff817cb3c4)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff817dc659)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff817f27e7)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/raw.c (ffffffff81824008)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff8182ccc8)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv6/raw.c (ffffffff818871e5)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81887a2a)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/exthdrs_core.c (ffffffff818a5bcc)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff818a6538)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In kernel/bpf/core.c (ffffffff8118ff74)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
```
In security/selinux/hooks.c (ffffffff813aab6c)
Location: include/linux/skbuff.h:3197
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813c3598)
Location: include/linux/skbuff.h:3197
Inline: True
```
```
In security/lsm_audit.c (ffffffff813c99f7)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff817c6502)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/filter.c (ffffffff817ea5a4)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff817fbcf6)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff8180fbe4)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/raw.c (ffffffff81844d37)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff8184e2c3)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv6/raw.c (ffffffff818ad71c)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff818ae03d)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/exthdrs_core.c (ffffffff818cc631)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff818ccf92)
Location: include/linux/skbuff.h:3197
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff813d0bcc)
Location: include/linux/skbuff.h:3318
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff813e9858)
Location: include/linux/skbuff.h:3318
Inline: True
```
```
In security/lsm_audit.c (ffffffff813efe87)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81840102)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81849d7a)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81865d24)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff818796b6)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff8188f114)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/raw.c (ffffffff818c4794)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff818cdfef)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv6/route.c (ffffffff8191a6c9)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff819303fc)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81930cbd)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/exthdrs_core.c (ffffffff819513e1)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81951d79)
Location: include/linux/skbuff.h:3318
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff813fde3d)
Location: include/linux/skbuff.h:3328
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8141a76b)
Location: include/linux/skbuff.h:3328
Inline: True
```
```
In security/lsm_audit.c (ffffffff814213f3)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff8188a622)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81893f79)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b3d45)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff818cb087)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff818e498b)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/raw.c (ffffffff8191a506)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff8192477a)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_send
```
```
In net/ipv6/route.c (ffffffff81975f63)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/raw.c (ffffffff81989079)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81989b3d)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/exthdrs_core.c (ffffffff819aa97c)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff819ab301)
Location: include/linux/skbuff.h:3328
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff81419cea)
Location: include/linux/skbuff.h:3407
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81436b4b)
Location: include/linux/skbuff.h:3407
Inline: True
```
```
In security/lsm_audit.c (ffffffff8143da89)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff818ab602)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff818b4963)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818d7cad)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff818f6228)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff8191188a)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
```
```
In net/ipv4/ip_sockglue.c (ffffffff8191ca59)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81948d5e)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff81953393)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff819abbab)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/raw.c (ffffffff819bf9b1)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c03fe)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff819cf98b)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e1467)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff819e1e1b)
Location: include/linux/skbuff.h:3407
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff81447747)
Location: include/linux/skbuff.h:3498
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8146480d)
Location: include/linux/skbuff.h:3498
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146b681)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff818f6e3a)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff819012a4)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff819275ed)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff819558a5)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff81971ef2)
Location: include/linux/skbuff.h:3498
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8197edb9)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff819ad3d7)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff819b7a72)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81a14758)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff81a2e654)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a2f230)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81a3e6a2)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a50225)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a50bba)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff814612d7)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8147e5dd)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (ffffffff81485461)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81928bba)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff819335d4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81959cad)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff8198bd45)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff819a88f2)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff819b61b9)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff819e4097)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff819ee772)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81a4b348)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff81a651ba)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a65d80)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81a75312)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a86e5f)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a877aa)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff814b42c8)
Location: include/linux/skbuff.h:3588
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814d3e7b)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814db5e9)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff819fcb3a)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81a00d76)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2ce9d)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a3479e)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81a639f4)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:3588
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9206b)
Location: include/linux/skbuff.h:3588
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa0a1d)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81ad1754)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81adc4e0)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81b411c8)
Location: include/linux/skbuff.h:3588
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5dacd)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5e9c8)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81b6f54e)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b8210f)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81b82c03)
Location: include/linux/skbuff.h:3588
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff814d1a28)
Location: include/linux/skbuff.h:3617
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f134b)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814f8a79)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff819fc77a)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81a01186)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a2e44d)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a36af8)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81a6bb54)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81a6f885)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:3617
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a9bf0b)
Location: include/linux/skbuff.h:3617
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81aa9e8d)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81add7d4)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81ae8c09)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81b4fc88)
Location: include/linux/skbuff.h:3617
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b6c27f)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b6d172)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81b7e07e)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b917ff)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81b92283)
Location: include/linux/skbuff.h:3617
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff814d7ed8)
Location: include/linux/skbuff.h:3682
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814f7feb)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff814ff857)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff819e2ff6)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff819e79e5)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81a159df)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81a1dc83)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81a542f2)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81a58139)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:3682
Inline: True
```
```
In net/ipv4/route.c (ffffffff81a86ec2)
Location: include/linux/skbuff.h:3682
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81a95059)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81ac88a4)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81ad41c7)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81b3daea)
Location: include/linux/skbuff.h:3682
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81b5a5df)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81b5b4dd)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81b6cc82)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81b809fc)
Location: include/linux/skbuff.h:3682
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81b813d5)
Location: include/linux/skbuff.h:3682
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
In security/selinux/hooks.c (ffffffff81530e98)
Location: include/linux/skbuff.h:3719
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81552bdb)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8155a8c7)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81a937b6)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81a98105)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81ac6c4f)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81ad1723)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81b0cfc8)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81b1111b)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:3719
Inline: True
```
```
In net/ipv4/route.c (ffffffff81b41682)
Location: include/linux/skbuff.h:3719
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81b504b9)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81b8710e)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81b92eb7)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81c0434a)
Location: include/linux/skbuff.h:3719
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c21c5f)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81c22bf3)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81c34b3c)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81c4ca1c)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81c4d3f5)
Location: include/linux/skbuff.h:3719
Inline: True
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
In security/selinux/hooks.c (ffffffff815c8388)
Location: include/linux/skbuff.h:4092
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff815ec73d)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff815f5668)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81c099f6)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81c0fdd0)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81c426ab)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81c4efeb)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81c9390d)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81c98215)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:4092
Inline: True
```
```
In net/ipv4/route.c (ffffffff81cce0e7)
Location: include/linux/skbuff.h:4092
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81cdea7c)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81d17dea)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81d250e5)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81d9e70e)
Location: include/linux/skbuff.h:4092
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81dbea7f)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81dbf702)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81dd24e0)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81dece70)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81ded948)
Location: include/linux/skbuff.h:4092
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81df367d)
Location: include/linux/skbuff.h:4092
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff81c06dc0-ffffffff81c06e07: __skb_header_pointer.part.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff816754a8)
Location: include/linux/skbuff.h:3988
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8169c43d)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816a614d)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81db9756)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81dbf810)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81df7cfb)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e0409b)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81e4f03d)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81e541c5)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:3988
Inline: True
```
```
In net/ipv4/route.c (ffffffff81e8e0a7)
Location: include/linux/skbuff.h:3988
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81e9e99c)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81ede66a)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81eec6c5)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81f6d5fe)
Location: include/linux/skbuff.h:3988
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81f8ef6f)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81f8fe51)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81fa3960)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81fc0c60)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81fc1858)
Location: include/linux/skbuff.h:3988
Inline: True
```
```
In net/packet/af_packet.c (ffffffff81fc844d)
Location: include/linux/skbuff.h:3988
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
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
In kernel/bpf/helpers.c (ffffffff813217c8)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
```
```
In security/selinux/hooks.c (ffffffff816ad828)
Location: include/linux/skbuff.h:4020
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff816d516d)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff816deb22)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81e29e06)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81e2f4ad)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81e6a33b)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:__bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81e7687a)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81eaa6dd)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81eaf9df)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:4020
Inline: True
```
```
In net/ipv4/route.c (ffffffff81eec7e7)
Location: include/linux/skbuff.h:4020
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81efd19b)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81f3d9b8)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff81f4c4b5)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81fcd71e)
Location: include/linux/skbuff.h:4020
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81fef7e3)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff81ff0693)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff8200423f)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_local.c (ffffffff8201d201)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff82021bef)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff820227d8)
Location: include/linux/skbuff.h:4020
Inline: True
```
```
In net/packet/af_packet.c (ffffffff82028f6d)
Location: include/linux/skbuff.h:4020
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff81e26b80-ffffffff81e26bc7: __skb_header_pointer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81343f60)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
```
```
In security/selinux/hooks.c (ffffffff816ea8b8)
Location: include/linux/skbuff.h:4049
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8171151d)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffff8171b6f2)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81ee7e76)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff81ef9715)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:skb_network_protocol
```
```
In net/core/filter.c (ffffffff81f2925b)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:__bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:INET_ECN_set_ce
```
```
In net/core/tso.c (ffffffff81f3683d)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/ethernet/eth.c (ffffffff81f6d18d)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/sched/sch_frag.c (ffffffff81f7244e)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
```
In net/sched/cls_api.c (0)
Location: include/linux/skbuff.h:4049
Inline: True
```
```
In net/ipv4/route.c (ffffffff81fb0847)
Location: include/linux/skbuff.h:4049
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc1195)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff82003add)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_input
```
```
In net/ipv4/icmp.c (ffffffff820125c5)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff8209af6e)
Location: include/linux/skbuff.h:4049
Inline: True
```
```
In net/ipv6/raw.c (ffffffff820bd3b3)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv6/raw.c:ipv6_raw_deliver
```
```
In net/ipv6/icmp.c (ffffffff820be264)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff820d2fff)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/seg6_local.c (ffffffff820ec1e1)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/exthdrs_core.c (ffffffff820f0d0f)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff820f18f8)
Location: include/linux/skbuff.h:4049
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f89ad)
Location: include/linux/skbuff.h:4049
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_parse_headers
```
**Symbols:**

```
ffffffff81ee4b10-ffffffff81ee4b57: __skb_header_pointer.part.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffff80001054e9dc)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffff80001056f7ec)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (ffff8000105779a8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffff800010bc4ef8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffff800010bd16d8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffff800010bfb920)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffff800010c36ddc)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffff800010c5822c)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffff800010c65e5c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffff800010c98aa8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffff800010ca4a3c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffff800010d0e3ac)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffff800010d2b024)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffff800010d2bc70)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffff800010d3dce4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffff800010d534d4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffff800010d54088)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (c0708388)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (c0722e58)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (c072a7cc)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (c0ce05c0)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (c0cec300)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c0d15b9c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (c0d49740)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (c0d67f50)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_multipath_l3_keys
```
```
In net/ipv4/ip_sockglue.c (c0d75a74)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (c0da6914)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (c0db0b90)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (c0e14d84)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (c0e2efd4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c0e2fc5c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (c0e40f88)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (c0e53e7c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (c0e54854)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (c0000000006afaa4)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (c0000000006d4d64)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (c0000000006e1080)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (c000000000c9f7fc)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (c000000000cafa80)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (c000000000ce3dc8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (c000000000d2ee20)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (c000000000d59bfc)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (c000000000d6a6c4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (c000000000daa2b8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (c000000000db7d14)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (c000000000e3a4dc)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (c000000000e5c3d8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (c000000000e5d548)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (c000000000e72218)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (c000000000e8bcfc)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (c000000000e8cb10)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffe0003a8ad4)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffe0003c57ea)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
```
```
In security/lsm_audit.c (ffffffe0003c9e96)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffe000751950)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffe00075bb68)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffe00077d84a)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffe0007a8768)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffe0007c240c)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd522)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffe0007f6ba0)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffe0007ffd4c)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffe000855ea0)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffe00086b510)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffe00086c0b4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffe00087a318)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffe00088b1d0)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffe00088bba2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff814598b7)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81476bbd)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (ffffffff8147da41)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff818c8bba)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff818d35d4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818f9c7d)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff8192bbb5)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff81948762)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81956029)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff81983f07)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff8198e512)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff819ea9d8)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff81a0484a)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a05410)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81a149a2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a264ef)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a26e3a)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff8144a2e7)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff814675dd)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (ffffffff8146e461)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81882afa)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff8188d464)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff818b3aad)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff818e5965)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff81902252)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff8190fb19)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff8193d9c7)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff81947fd2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff819a7798)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff819c160a)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff819c21d0)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff819d1762)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff819e32af)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff819e3bfa)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff81455957)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81472c5d)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (ffffffff81479ae1)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff81919bba)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff819245d4)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8194acad)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff8197cd45)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff8199d322)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:get_l4proto
  - net/netfilter/nf_conntrack_core.c:get_l4proto
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a61d2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a71f2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_proto_icmp.c (ffffffff819a7a75)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_pkt_to_tuple
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a8925)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_pkt_to_tuple
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9bd7)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819ab0c6)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819ab971)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
```
```
In net/ipv4/route.c (ffffffff819b2f32)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff819c07f9)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff819ee6d7)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff819f8db2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81a55458)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff81a6f2ca)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a6fe90)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81a7f422)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a9209f)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a929ea)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
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
In security/selinux/hooks.c (ffffffff81470c47)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff8148a54d)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In security/lsm_audit.c (ffffffff81491591)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
```
```
In net/core/flow_dissector.c (ffffffff8193adfa)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_get_poff
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/flow_dissector.c:__skb_flow_get_ports
```
```
In net/core/dev.c (ffffffff81945a64)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff8196c5bd)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
```
```
In net/ethernet/eth.c (ffffffff8199f2b5)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_type_trans
```
```
In net/ipv4/route.c (ffffffff819bc602)
Location: include/linux/skbuff.h:3565
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff819ca1d9)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
```
```
In net/ipv4/raw.c (ffffffff819f872d)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_local_deliver
```
```
In net/ipv4/icmp.c (ffffffff81a02d32)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv4/icmp.c:__icmp_send
```
```
In net/ipv6/route.c (ffffffff81a61458)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/raw.c (ffffffff81a7b8ef)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
```
In net/ipv6/icmp.c (ffffffff81a7c4cc)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
```
```
In net/ipv6/datagram.c (ffffffff81a8bce2)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
```
```
In net/ipv6/exthdrs_core.c (ffffffff81a9e14f)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
```
```
In net/ipv6/output_core.c (ffffffff81a9eaea)
Location: include/linux/skbuff.h:3565
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
```
</details>
</li>
</ul>

## Differences
