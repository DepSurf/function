# Function: <code>bpf_prog_run_save_cb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81730aa2)
Location: include/linux/filter.h:353
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter
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
In net/core/filter.c (ffffffff8179b767)
Location: include/linux/filter.h:406
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff817a008b)
Location: include/linux/filter.h:406
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In kernel/bpf/cgroup.c (ffffffff81197672)
Location: include/linux/filter.h:476
Inline: True
```
```
In net/core/filter.c (ffffffff817ca916)
Location: include/linux/filter.h:476
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff817cea5b)
Location: include/linux/filter.h:476
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff817d9dd9)
Location: include/linux/filter.h:476
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
In kernel/bpf/cgroup.c (ffffffff8119f30c)
Location: include/linux/filter.h:529
Inline: True
```
```
In net/core/filter.c (ffffffff817e9ade)
Location: include/linux/filter.h:529
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff817edef9)
Location: include/linux/filter.h:529
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff817f8e88)
Location: include/linux/filter.h:529
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
In kernel/bpf/cgroup.c (ffffffff811b2523)
Location: include/linux/filter.h:534
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff8186514e)
Location: include/linux/filter.h:534
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff8186a13d)
Location: include/linux/filter.h:534
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81876787)
Location: include/linux/filter.h:534
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
In kernel/bpf/cgroup.c (ffffffff811d1bac)
Location: include/linux/filter.h:574
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_run_filter_skb
```
```
In net/core/filter.c (ffffffff818b2c6e)
Location: include/linux/filter.h:574
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffff818b9e26)
Location: include/linux/filter.h:574
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818c7eb7)
Location: include/linux/filter.h:574
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819a8f3d)
Location: include/linux/filter.h:574
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
In net/core/filter.c (ffffffff818d5b97)
Location: include/linux/filter.h:614
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff818e0b8d)
Location: include/linux/filter.h:614
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818f1011)
Location: include/linux/filter.h:614
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819dfef2)
Location: include/linux/filter.h:614
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
In net/core/filter.c (ffffffff81923335)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff8192f230)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff819429d1)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4eb00)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffff8195555d)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff819614a0)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81977921)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a857a0)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffff81a2bb16)
Location: include/linux/filter.h:699
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a34b21)
Location: include/linux/filter.h:699
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a4ca0b)
Location: include/linux/filter.h:699
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b80736)
Location: include/linux/filter.h:699
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
In net/core/filter.c (ffffffff81a2d0a6)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a36e61)
Location: include/linux/filter.h:708
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a526a6)
Location: include/linux/filter.h:708
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ffb6)
Location: include/linux/filter.h:708
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
In net/core/filter.c (ffffffff81a14115)
Location: include/linux/filter.h:751
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81a1dee7)
Location: include/linux/filter.h:751
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81a37d8b)
Location: include/linux/filter.h:751
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b7f0e8)
Location: include/linux/filter.h:751
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
In net/core/filter.c (ffffffff81ac59e5)
Location: include/linux/filter.h:763
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81ad1977)
Location: include/linux/filter.h:763
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:run_bpf_filter
```
```
In net/core/lwt_bpf.c (ffffffff81aedb9b)
Location: include/linux/filter.h:763
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a938)
Location: include/linux/filter.h:763
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
In net/core/filter.c (ffffffff81c3c9da)
Location: include/linux/filter.h:766
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81c4f61e)
Location: include/linux/filter.h:766
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81c70a7d)
Location: include/linux/filter.h:766
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81dea256)
Location: include/linux/filter.h:766
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
In net/core/filter.c (ffffffff81dfa40c)
Location: include/linux/filter.h:738
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81e045b9)
Location: include/linux/filter.h:738
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81e28aad)
Location: include/linux/filter.h:738
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fbdb16)
Location: include/linux/filter.h:738
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
In net/core/filter.c (ffffffff81e6b7c0)
Location: include/linux/filter.h:738
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81e76e09)
Location: include/linux/filter.h:738
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81e9e0cd)
Location: include/linux/filter.h:738
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201eb36)
Location: include/linux/filter.h:738
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
In net/core/filter.c (ffffffff81f2a970)
Location: include/linux/filter.h:789
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81f36dc9)
Location: include/linux/filter.h:789
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81f6084d)
Location: include/linux/filter.h:789
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff820edc66)
Location: include/linux/filter.h:789
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
In net/core/filter.c (ffff800010c02058)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffff800010c04d20)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffff800010c1ecf0)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d5183c)
Location: include/linux/filter.h:670
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
In net/core/filter.c (c0d10458)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c0d1e1e8)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (c0d3606c)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (c0e523dc)
Location: include/linux/filter.h:670
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
In net/core/filter.c (c000000000cdce10)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (c000000000ceeee8)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (c000000000d0fc34)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e89aa8)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffe000778592)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffe00078397e)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffe000797d8e)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe000889a22)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffff818f552d)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81901470)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81917791)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a24e30)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffff818af35d)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff818bb2a0)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff818d1541)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e1bf0)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffff8194655d)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff819524a0)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff81968921)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8f8b0)
Location: include/linux/filter.h:670
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
In net/core/filter.c (ffffffff81967e57)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_trim_cap
```
```
In net/core/sock_reuseport.c (ffffffff81973eeb)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
```
In net/core/lwt_bpf.c (ffffffff8198acd8)
Location: include/linux/filter.h:670
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9c639)
Location: include/linux/filter.h:670
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_bpf
```
</details>
</li>
</ul>

## Differences
