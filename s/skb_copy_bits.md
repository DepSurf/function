# Function: <code>skb_copy_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81171540)
Location: kernel/bpf/core.c:795
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:skb_copy
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_try_coalesce
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
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:icmp_send
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81707060-ffffffff81707341: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117f360)
Location: kernel/bpf/core.c:1088
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:icmp_send
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8176d320-ffffffff8176d5f6: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118b1d0)
Location: kernel/bpf/core.c:1171
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:icmp_send
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8179a4c0-ffffffff8179a790: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118fd30)
Location: kernel/bpf/core.c:1428
Inline: False
Direct callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff817ba4d0-ffffffff817ba72f: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e4e0)
Location: kernel/bpf/core.c:1674
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff818328c0-ffffffff81832b1d: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2d20)
Location: kernel/bpf/core.c:1844
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8187cde0-ffffffff8187d034: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c18e0)
Location: kernel/bpf/core.c:2098
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/route.c:fib_multipath_hash
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/route.c:rt6_multipath_hash
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8189da00-ffffffff8189dc4b: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d2010)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff818ef1a3-ffffffff818ef1e1: skb_copy_bits.cold (STB_LOCAL)
ffffffff818e8200-ffffffff818e8405: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de5b0)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8191a430-ffffffff8191a64a: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb2b0)
Location: kernel/bpf/core.c:2225
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819ec1a0-ffffffff819ec3b6: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa460)
Location: kernel/bpf/core.c:2274
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884_validate
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819ebec0-ffffffff819ec0d6: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fb3a0)
Location: kernel/bpf/core.c:2408
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:icmp_echo
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff819d1a50-ffffffff819d1c5c: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122ca80)
Location: kernel/bpf/core.c:2428
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81a815f0-ffffffff81a817fc: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e870)
Location: kernel/bpf/core.c:2728
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:bounce_skb
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81bf64a0-ffffffff81bf66de: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c3fc0)
Location: kernel/bpf/core.c:2729
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81da5d00-ffffffff81da5f20: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812eaf70)
Location: kernel/bpf/core.c:2751
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:qdisc_pkt_len_init
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:__bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81e14dd0-ffffffff81e15009: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81309490)
Location: kernel/bpf/core.c:2931
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_dynptr_slice
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_gre
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:skb_flow_get_icmp_tci
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:skb_network_protocol
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_ecn_set_ce
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:__bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/filter.c:INET_ECN_set_ce
  - net/core/tso.c:tso_start
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
  - net/ethernet/eth.c:eth_type_trans
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
  - net/ipv4/ip_fragment.c:ip_check_defrag
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
  - net/ipv4/icmp.c:icmp_timestamp
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:icmp_build_probe
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmpv6
  - net/ipv4/ip_tunnel_core.c:iptunnel_pmtud_build_icmp
  - net/ipv4/ipmr.c:igmpmsg_netlink_event
  - net/xfrm/espintcp.c:espintcp_parse
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/xfrm/espintcp.c:espintcp_rcv
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_push_pending_frames
  - net/ipv6/raw.c:ipv6_raw_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:mrt6msg_netlink_event
  - net/ipv6/seg6_local.c:seg6_pop_srh
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/packet/af_packet.c:tpacket_rcv
  - net/packet/af_packet.c:packet_parse_headers
  - net/mctp/route.c:mctp_do_fragment_route
```
**Symbols:**

```
ffffffff81ed1a00-ffffffff81ed1c39: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f880)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffff800010bb2e48-ffff800010bb3070: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492c68)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/route.c:ip_multipath_l3_keys
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
c0cd11e0-c0cd14d4: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000304900)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
c000000000c8b100-c000000000c8b420: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d6e6)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/smack/smack_lsm.c:smk_skb_to_addr_ipv6
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffe0007425f8-ffffffe0007427ee: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6bd0)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff818ba430-ffffffff818ba64a: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c9990)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff81874380-ffffffff8187459a: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d49a0)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/netfilter/nfnetlink_log.c:__build_packet_message
  - net/netfilter/nf_conntrack_core.c:get_l4proto
  - net/netfilter/nf_conntrack_core.c:get_l4proto
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
  - net/netfilter/nf_conntrack_core.c:nf_ct_get_tuple
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmpv4_error
  - net/netfilter/nf_conntrack_proto_icmp.c:icmp_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_error
  - net/netfilter/nf_conntrack_proto_icmpv6.c:icmpv6_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
  - net/netfilter/nf_conntrack_proto_gre.c:gre_pkt_to_tuple
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_gather
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8190b430-ffffffff8190b64a: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_copy_bits(const struct sk_buff *skb, int offset, void *to, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2cd0)
Location: kernel/bpf/core.c:2102
Inline: False
Direct callers:
  - security/lsm_audit.c:ipv6_skb_to_auditdata
  - drivers/net/ppp/ppp_generic.c:ppp_receive_nonmp_frame
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_copy_bits
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:skb_copy
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
  - net/core/flow_dissector.c:__skb_flow_get_ports
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/filter.c:sk_reuseport_load_bytes
  - net/core/filter.c:bpf_skb_copy
  - net/core/filter.c:bpf_flow_dissector_load_bytes
  - net/core/filter.c:bpf_skb_load_bytes
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
  - net/ethernet/eth.c:eth_type_trans
  - net/ipv4/ip_output.c:ip_frag_next
  - net/ipv4/ip_sockglue.c:ip_cmsg_recv_offset
  - net/ipv4/tcp_input.c:tcp_collapse
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/ipmr.c:ipmr_cache_report
  - net/ipv6/ip6_output.c:ip6_frag_next
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/route.c:ip6_multipath_l3_keys
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/raw.c:rawv6_sendmsg
  - net/ipv6/raw.c:raw6_local_deliver
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/icmp.c:icmp6_send
  - net/ipv6/datagram.c:ip6_datagram_recv_specific_ctl
  - net/ipv6/ip6mr.c:ip6mr_cache_report
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_find_hdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/exthdrs_core.c:ipv6_skip_exthdr
  - net/ipv6/output_core.c:ipv6_proxy_select_ident
  - net/packet/af_packet.c:tpacket_rcv
```
**Symbols:**

```
ffffffff8192c530-ffffffff8192c761: skb_copy_bits (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
