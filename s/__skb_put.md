# Function: <code>__skb_put</code>

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
In net/core/skbuff.c (ffffffff8170acaf)
Location: include/linux/skbuff.h:1805
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/netlink/af_netlink.c (ffffffff8174e967)
Location: include/linux/skbuff.h:1805
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817729e3)
Location: include/linux/skbuff.h:1906
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179fb7a)
Location: include/linux/skbuff.h:1921
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
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
In net/core/skbuff.c (ffffffff817bea6c)
Location: include/linux/skbuff.h:1914
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff8180c9a1)
Location: include/linux/skbuff.h:1914
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff811afbee)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In net/core/skbuff.c (ffffffff8183835d)
Location: include/linux/skbuff.h:2001
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff8188b988)
Location: include/linux/skbuff.h:2001
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
In kernel/bpf/cpumap.c (ffffffff811cabe1)
Location: include/linux/skbuff.h:2012
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8188288d)
Location: include/linux/skbuff.h:2012
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff818df3b3)
Location: include/linux/skbuff.h:2012
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff811de4db)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff818a3325)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff8190bec8)
Location: include/linux/skbuff.h:2090
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff811f3d73)
Location: include/linux/skbuff.h:2178
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff818ee101)
Location: include/linux/skbuff.h:2178
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff8196d692)
Location: include/linux/skbuff.h:2178
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff81200b13)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff819201f4)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff819a4107)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff81227d79)
Location: include/linux/skbuff.h:2215
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f37d7)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff81a7ec42)
Location: include/linux/skbuff.h:2215
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff8122ead9)
Location: include/linux/skbuff.h:2236
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In net/core/skbuff.c (ffffffff819f3801)
Location: include/linux/skbuff.h:2236
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff81a88583)
Location: include/linux/skbuff.h:2236
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/skbuff.c (ffffffff819d9a21)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/xdp.c (ffffffff81a1f94e)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/bpf/test_run.c (ffffffff81a717e3)
Location: include/linux/skbuff.h:2252
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/skbuff.c (ffffffff81a899dc)
Location: include/linux/skbuff.h:2281
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/xdp.c (ffffffff81ad390e)
Location: include/linux/skbuff.h:2281
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/bpf/test_run.c (ffffffff81b2af02)
Location: include/linux/skbuff.h:2281
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/skbuff.c (ffffffff81bfec6d)
Location: include/linux/skbuff.h:2640
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/xdp.c (ffffffff81c512cc)
Location: include/linux/skbuff.h:2640
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/bpf/test_run.c (ffffffff81cb510d)
Location: include/linux/skbuff.h:2640
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/core/skbuff.c (ffffffff81dad6ae)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/xdp.c (ffffffff81e06a70)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/netlink/af_netlink.c (ffffffff81e6c94e)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/bpf/test_run.c (ffffffff81e7366b)
Location: include/linux/skbuff.h:2537
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In drivers/net/virtio_net.c (ffffffff81c555ff)
Location: include/linux/skbuff.h:2580
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In net/core/skbuff.c (ffffffff81e1d5cf)
Location: include/linux/skbuff.h:2580
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/xdp.c (ffffffff81e7838b)
Location: include/linux/skbuff.h:2580
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/netlink/af_netlink.c (ffffffff81ec89ae)
Location: include/linux/skbuff.h:2580
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/bpf/test_run.c (ffffffff81ed0b43)
Location: include/linux/skbuff.h:2580
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In drivers/net/virtio_net.c (ffffffff81d0bc9a)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In net/core/skbuff.c (ffffffff81edacd3)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/core/xdp.c (ffffffff81f3834b)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
```
In net/netlink/af_netlink.c (ffffffff81f8bc54)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_ack
```
```
In net/bpf/test_run.c (ffffffff81f944a3)
Location: include/linux/skbuff.h:2587
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffff8000102881fc)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffff800010bbab24)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffff800010c53560)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (c04b84d0)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (c0cd743c)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (c0d62e84)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (c00000000033389c)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (c000000000c9385c)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (c000000000d52c0c)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffe0001bceac)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffe000749d12)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffe0007bde22)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff811f9133)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff818c01f4)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff81943f77)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff811ebe83)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8187a134)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff818fda67)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff811f6f03)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff819111f4)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff81995107)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In kernel/bpf/cpumap.c (ffffffff812051ea)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff81932354)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment
```
```
In net/bpf/test_run.c (ffffffff819b7c87)
Location: include/linux/skbuff.h:2192
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
</details>
</li>
</ul>

## Differences
