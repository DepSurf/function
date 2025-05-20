# Function: <code>skb_metadata_len</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b0a01)
Location: include/linux/skbuff.h:3428
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_parse_func_strparser
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In net/core/dev.c (ffffffff8184b579)
Location: include/linux/skbuff.h:3428
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81866678)
Location: include/linux/skbuff.h:3428
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8187674e)
Location: include/linux/skbuff.h:3428
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8188ba0c)
Location: include/linux/skbuff.h:3428
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/dev.c (ffffffff81895939)
Location: include/linux/skbuff.h:3438
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff818b5fd9)
Location: include/linux/skbuff.h:3438
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff818c7e92)
Location: include/linux/skbuff.h:3438
Inline: True
```
```
In net/bpf/test_run.c (ffffffff818df444)
Location: include/linux/skbuff.h:3438
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff819a8f16)
Location: include/linux/skbuff.h:3438
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/flow_dissector.c (ffffffff818a9953)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/dev.c (ffffffff818b7617)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff818db04f)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff818f0ff2)
Location: include/linux/skbuff.h:3517
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8190c02f)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff819dfed1)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff818ecce6)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8190344c)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff81927e09)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff819436e5)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff8196d719)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eada)
Location: include/linux/skbuff.h:3626
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff8191ee06)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff819361fc)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8195a1a9)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff819786d3)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff819a4184)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a8577a)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff819f084f)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81a009f2)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/core/filter.c (ffffffff81a30604)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a4d683)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81a7ee69)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81b80710)
Location: include/linux/skbuff.h:3719
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff819f000f)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81a00e02)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/core/filter.c (ffffffff81a32935)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a5334a)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81a888dd)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ff90)
Location: include/linux/skbuff.h:3748
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff819d783f)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff819e75b2)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/core/filter.c (ffffffff81a19a51)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a38b76)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81a71b3d)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0c2)
Location: include/linux/skbuff.h:3812
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff81a8607f)
Location: include/linux/skbuff.h:3849
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81a982b1)
Location: include/linux/skbuff.h:3849
Inline: True
Inline callers:
  - net/core/dev.c:gro_list_prepare
  - net/core/dev.c:gro_list_prepare
```
```
In net/core/filter.c (ffffffff81acbcc1)
Location: include/linux/skbuff.h:3849
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81aeea56)
Location: include/linux/skbuff.h:3849
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81b2b254)
Location: include/linux/skbuff.h:3849
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a912)
Location: include/linux/skbuff.h:3849
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff81bf9077)
Location: include/linux/skbuff.h:4268
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81c48132)
Location: include/linux/skbuff.h:4268
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/gro.c (ffffffff81c53a85)
Location: include/linux/skbuff.h:4268
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/lwt_bpf.c (ffffffff81c7190d)
Location: include/linux/skbuff.h:4268
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81cb54c8)
Location: include/linux/skbuff.h:4268
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81dea236)
Location: include/linux/skbuff.h:4268
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff81daa657)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81dfcc32)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/gro.c (ffffffff81e0920c)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/lwt_bpf.c (ffffffff81e299fd)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81e7398c)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdaf6)
Location: include/linux/skbuff.h:4164
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff81e1b817)
Location: include/linux/skbuff.h:4196
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/filter.c (ffffffff81e6dd02)
Location: include/linux/skbuff.h:4196
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/gro.c (ffffffff81e7b9ce)
Location: include/linux/skbuff.h:4196
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/lwt_bpf.c (ffffffff81e9f03e)
Location: include/linux/skbuff.h:4196
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81ecf6b0)
Location: include/linux/skbuff.h:4196
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff8201eb16)
Location: include/linux/skbuff.h:4196
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In drivers/net/netkit.c (ffffffff81ce529a)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In net/core/skbuff.c (ffffffff81ed8dd7)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_reorder_vlan_header
```
```
In net/core/dev.c (ffffffff81ef9ac9)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f2d6d2)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/gro.c (ffffffff81f3bc3a)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/core/gro.c:gro_list_prepare
  - net/core/gro.c:gro_list_prepare
```
```
In net/core/lwt_bpf.c (ffffffff81f617ae)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81f93000)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff820edc46)
Location: include/linux/skbuff.h:4233
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffff800010bb9608)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffff800010bd4884)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffff800010c004d8)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffff800010c1f324)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffff800010c5371c)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffff800010d51810)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (c0cd6098)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c0ceee54)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (c0d1681c)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (c0d36ee4)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (c0d630b8)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (c0e523c8)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (c000000000c91bc4)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (c000000000cb3974)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (c000000000ce6bf8)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (c000000000d111e4)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (c000000000d52e80)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (c000000000e89a84)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffe000748b60)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffe00075e682)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffe00077e35a)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffe000798a94)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffe0007bde80)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffe0008899fc)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff818bee06)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff818d61cc)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff818fa179)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81918543)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81943ff4)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a24e0a)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff81878d46)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff8189000c)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff818b3fa9)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff818d22f3)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff818fdae4)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff819e1bca)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff8190fe06)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff819271fc)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8194b1a9)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff819696d3)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81995184)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f88a)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
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
In net/core/skbuff.c (ffffffff81930f36)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_vlan_untag
```
```
In net/core/dev.c (ffffffff81948866)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/dev.c:dev_gro_receive
  - net/core/dev.c:dev_gro_receive
```
```
In net/core/filter.c (ffffffff8196cab9)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_adjust_srh
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_push_seg6_encap
  - net/core/filter.c:bpf_skb_change_head
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_skb_adjust_room
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8198bab3)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff819b7d04)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c613)
Location: include/linux/skbuff.h:3693
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
</ul>

## Differences
