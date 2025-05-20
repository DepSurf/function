# Function: <code>bpf_compute_data_pointers</code>

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
In kernel/bpf/sockmap.c (ffffffff811b09fa)
Location: include/linux/filter.h:506
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_parse_func_strparser
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In net/core/filter.c (ffffffff81866678)
Location: include/linux/filter.h:506
Inline: True
Inline callers:
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
In net/core/lwt_bpf.c (ffffffff8187674e)
Location: include/linux/filter.h:506
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8188ba0c)
Location: include/linux/filter.h:506
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
In net/core/filter.c (ffffffff818b5fc5)
Location: include/linux/filter.h:546
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
In net/core/lwt_bpf.c (ffffffff818c7e7e)
Location: include/linux/filter.h:546
Inline: True
```
```
In net/bpf/test_run.c (ffffffff818df436)
Location: include/linux/filter.h:546
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff819a8f02)
Location: include/linux/filter.h:546
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
In net/core/flow_dissector.c (ffffffff818a994c)
Location: include/linux/filter.h:545
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/filter.c (ffffffff818db03b)
Location: include/linux/filter.h:545
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
In net/core/lwt_bpf.c (ffffffff818f0fde)
Location: include/linux/filter.h:545
Inline: True
```
```
In net/bpf/test_run.c (ffffffff8190c021)
Location: include/linux/filter.h:545
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff819dfebd)
Location: include/linux/filter.h:545
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
In net/core/filter.c (ffffffff81927df5)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffffffff819436d1)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff8196d70b)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eac2)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffff8195a195)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffffffff819786bb)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff819a4176)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a85762)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffff81a305f0)
Location: include/linux/filter.h:629
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
In net/core/lwt_bpf.c (ffffffff81a4d66f)
Location: include/linux/filter.h:629
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81a7ee5b)
Location: include/linux/filter.h:629
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81b806f8)
Location: include/linux/filter.h:629
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
In net/core/filter.c (ffffffff81a32921)
Location: include/linux/filter.h:638
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
In net/core/lwt_bpf.c (ffffffff81a53336)
Location: include/linux/filter.h:638
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81a888c8)
Location: include/linux/filter.h:638
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ff78)
Location: include/linux/filter.h:638
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
In net/core/filter.c (ffffffff81a19a3d)
Location: include/linux/filter.h:681
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
In net/core/lwt_bpf.c (ffffffff81a38b62)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81a71b28)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0aa)
Location: include/linux/filter.h:681
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
In net/core/filter.c (ffffffff81acbcad)
Location: include/linux/filter.h:692
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
In net/core/lwt_bpf.c (ffffffff81aeea42)
Location: include/linux/filter.h:692
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81b2b23f)
Location: include/linux/filter.h:692
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a8fa)
Location: include/linux/filter.h:692
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
In net/core/filter.c (ffffffff81c4811e)
Location: include/linux/filter.h:695
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
In net/core/lwt_bpf.c (ffffffff81c718f9)
Location: include/linux/filter.h:695
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81cb54b3)
Location: include/linux/filter.h:695
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81dea222)
Location: include/linux/filter.h:695
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
In net/core/filter.c (ffffffff81dfcc1e)
Location: include/linux/filter.h:667
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
In net/core/lwt_bpf.c (ffffffff81e299e9)
Location: include/linux/filter.h:667
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81e73977)
Location: include/linux/filter.h:667
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdae2)
Location: include/linux/filter.h:667
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
In net/core/filter.c (ffffffff81e6dcee)
Location: include/linux/filter.h:667
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
In net/core/lwt_bpf.c (ffffffff81e9f02a)
Location: include/linux/filter.h:667
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81ecf69b)
Location: include/linux/filter.h:667
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff8201eb02)
Location: include/linux/filter.h:667
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
In drivers/net/netkit.c (ffffffff81ce5286)
Location: include/linux/filter.h:718
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In net/core/dev.c (ffffffff81ef9ab5)
Location: include/linux/filter.h:718
Inline: True
Inline callers:
  - net/core/dev.c:__dev_queue_xmit
```
```
In net/core/filter.c (ffffffff81f2d6be)
Location: include/linux/filter.h:718
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
In net/core/lwt_bpf.c (ffffffff81f6179a)
Location: include/linux/filter.h:718
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81f92feb)
Location: include/linux/filter.h:718
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff820edc32)
Location: include/linux/filter.h:718
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
In net/core/filter.c (ffff800010c004d4)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffff800010c1f320)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffff800010c53714)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffff800010d5180c)
Location: include/linux/filter.h:601
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
In net/core/filter.c (c0d16804)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (c0d36ecc)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (c0d630a4)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (c0e523b4)
Location: include/linux/filter.h:601
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
In net/core/filter.c (c000000000ce6be0)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (c000000000d111cc)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (c000000000d52e70)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (c000000000e89a70)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffe00077e35a)
Location: include/linux/filter.h:601
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
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffe0007bde80)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffe0008899fc)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffff818fa165)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffffffff8191852b)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81943fe6)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a24df2)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffff818b3f95)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffffffff818d22db)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff818fdad6)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff819e1bb2)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffff8194b195)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffffffff819696bb)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff81995176)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f872)
Location: include/linux/filter.h:601
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
In net/core/filter.c (ffffffff8196caa5)
Location: include/linux/filter.h:601
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
In net/core/lwt_bpf.c (ffffffff8198ba9b)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/bpf/test_run.c (ffffffff819b7cf6)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c5fb)
Location: include/linux/filter.h:601
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
</ul>

## Differences
