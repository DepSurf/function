# Function: <code>sock_cgroup_ptr</code>

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
In kernel/cgroup.c (ffffffff81121805)
Location: include/linux/cgroup.h:593
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_sk_alloc
```
```
In net/core/filter.c (ffffffff8179b651)
Location: include/linux/cgroup.h:593
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup.c (ffffffff81129da5)
Location: include/linux/cgroup.h:615
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_sk_free
  - kernel/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81197585)
Location: include/linux/cgroup.h:615
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
```
```
In net/core/filter.c (ffffffff817c9656)
Location: include/linux/cgroup.h:615
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81128b85)
Location: include/linux/cgroup.h:656
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff8119f205)
Location: include/linux/cgroup.h:656
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
```
```
In net/core/filter.c (ffffffff817e8590)
Location: include/linux/cgroup.h:656
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff811351b5)
Location: include/linux/cgroup.h:764
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811b21f6)
Location: include/linux/cgroup.h:764
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818638f3)
Location: include/linux/cgroup.h:764
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff811438d5)
Location: include/linux/cgroup.h:772
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811d1785)
Location: include/linux/cgroup.h:772
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818aea66)
Location: include/linux/cgroup.h:772
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8114f3e5)
Location: include/linux/cgroup.h:810
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811e1325)
Location: include/linux/cgroup.h:810
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818d2d6f)
Location: include/linux/cgroup.h:810
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8115b275)
Location: include/linux/cgroup.h:825
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811f821d)
Location: include/linux/cgroup.h:825
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff8191fe62)
Location: include/linux/cgroup.h:825
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81166f35)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81204ec8)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81952099)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81178645)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff8122c265)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81a2c14f)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff811753f5)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff81234665)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81a2e874)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81bc35c1)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81175f65)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff812390d5)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81a15ebd)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81bb3c31)
Location: include/linux/cgroup.h:828
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff8119d535)
Location: include/linux/cgroup.h:836
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff812763a1)
Location: include/linux/cgroup.h:836
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81acc057)
Location: include/linux/cgroup.h:836
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81c8237f)
Location: include/linux/cgroup.h:836
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff811cd875)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff812c5def)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/socket.c (ffffffff81be9d2a)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/filter.c (ffffffff81c488ac)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81cd8f43)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a93a)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/mptcp/subflow.c (ffffffff81e280b2)
Location: include/linux/cgroup.h:833
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81210f25)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff8132b36f)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
```
```
In net/socket.c (ffffffff81d965ea)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/filter.c (ffffffff81dfd3d2)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81e99589)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff81f588ea)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/mptcp/subflow.c (ffffffff82000014)
Location: include/linux/cgroup.h:760
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81226915)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff8135b58f)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
```
```
In net/socket.c (ffffffff81e04c3a)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - net/socket.c:__sys_getsockopt
  - net/socket.c:__sys_setsockopt
```
```
In net/core/filter.c (ffffffff81e6de9d)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81ef7e97)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff81fb864c)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/mptcp/subflow.c (ffffffff8207c1e0)
Location: include/linux/cgroup.h:758
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff8123e5a5)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
```
```
In kernel/bpf/cgroup.c (ffffffff8138421f)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt_kern
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_socket
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_lsm_sock
```
```
In net/socket.c (ffffffff81ebdb6b)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - net/socket.c:do_sock_getsockopt
  - net/socket.c:do_sock_setsockopt
```
```
In net/core/filter.c (ffffffff81f2cf2d)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/ipv4/ip_output.c (ffffffff81fbbd64)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv6/ip6_output.c (ffffffff82085c39)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/mptcp/subflow.c (ffffffff8215169c)
Location: include/linux/cgroup.h:756
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffff8000101d8e40)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffff80001028e350)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffff800010bf4274)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (c041bc6c)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (c04bd2fc)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (c0d0ca48)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (c0000000002462d0)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (c000000000339d40)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (c000000000cd93c8)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffe000151dbc)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffe0001c1536)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffe00077572a)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8115f555)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811fd4e8)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818f2069)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff811527e5)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811f0238)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818abe99)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8115d325)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff811fb2b8)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81943099)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8116a525)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_free
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
```
In kernel/bpf/cgroup.c (ffffffff81209e28)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_getsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_setsockopt
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_ops
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sock_addr
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_sk
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff81964989)
Location: include/linux/cgroup.h:827
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
</details>
</li>
</ul>

## Differences
