# Function: <code>skb_metadata_set</code>

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
In kernel/bpf/cpumap.c (ffffffff811afc50)
Location: include/linux/skbuff.h:3481
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In net/core/skbuff.c (ffffffff81834813)
Location: include/linux/skbuff.h:3481
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff8184a828)
Location: include/linux/skbuff.h:3481
Inline: True
Inline callers:
  - net/core/dev.c:do_xdp_generic
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
In kernel/bpf/cpumap.c (ffffffff811cac01)
Location: include/linux/skbuff.h:3491
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8187e709)
Location: include/linux/skbuff.h:3491
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81894bac)
Location: include/linux/skbuff.h:3491
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
In kernel/bpf/cpumap.c (ffffffff811de4f8)
Location: include/linux/skbuff.h:3576
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8189f8ba)
Location: include/linux/skbuff.h:3576
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff818b562b)
Location: include/linux/skbuff.h:3576
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
In kernel/bpf/cpumap.c (ffffffff811f3d99)
Location: include/linux/skbuff.h:3685
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff818ea0fa)
Location: include/linux/skbuff.h:3685
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff818fae0e)
Location: include/linux/skbuff.h:3685
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff81200b39)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8191c27a)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff8192cf5c)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff81227dd3)
Location: include/linux/skbuff.h:3778
Inline: True
```
```
In net/core/skbuff.c (ffffffff819f0086)
Location: include/linux/skbuff.h:3778
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81a069a3)
Location: include/linux/skbuff.h:3778
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff8122eb33)
Location: include/linux/skbuff.h:3807
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
```
In net/core/skbuff.c (ffffffff819efd36)
Location: include/linux/skbuff.h:3807
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81a07f75)
Location: include/linux/skbuff.h:3807
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In net/core/skbuff.c (ffffffff819d398a)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff819ea8d9)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
```
In net/core/xdp.c (ffffffff81a1f9a9)
Location: include/linux/skbuff.h:3871
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In net/core/skbuff.c (ffffffff81a836ea)
Location: include/linux/skbuff.h:3908
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81aa1e76)
Location: include/linux/skbuff.h:3908
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/xdp.c (ffffffff81ad3969)
Location: include/linux/skbuff.h:3908
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In net/core/skbuff.c (ffffffff81bf8eaa)
Location: include/linux/skbuff.h:4327
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81c1a068)
Location: include/linux/skbuff.h:4327
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/xdp.c (ffffffff81c51368)
Location: include/linux/skbuff.h:4327
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In net/core/skbuff.c (ffffffff81da7dc5)
Location: include/linux/skbuff.h:4223
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81dcb0e8)
Location: include/linux/skbuff.h:4223
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/xdp.c (ffffffff81e06b04)
Location: include/linux/skbuff.h:4223
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In drivers/net/virtio_net.c (ffffffff81c5561b)
Location: include/linux/skbuff.h:4255
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
```
```
In net/core/skbuff.c (ffffffff81e16856)
Location: include/linux/skbuff.h:4255
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81e3bc74)
Location: include/linux/skbuff.h:4255
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/xdp.c (ffffffff81e783fb)
Location: include/linux/skbuff.h:4255
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In drivers/net/virtio_net.c (ffffffff81d0bcb6)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_small_xdp
```
```
In net/core/skbuff.c (ffffffff81ed3c76)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81efa1b0)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/core/dev.c:bpf_prog_run_generic_xdp
```
```
In net/core/xdp.c (ffffffff81f383bb)
Location: include/linux/skbuff.h:4295
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
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
In kernel/bpf/cpumap.c (ffff80001028821c)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffff800010bb6800)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffff800010bcf8b4)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (c04b84f4)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (c0cd36a8)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (c0ce5bd4)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (c0000000003338c0)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (c000000000c8e130)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (c000000000ca67d4)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffe0001bcede)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffe000746546)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffe000755cc6)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff811f9159)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff818bc27a)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff818ccf5c)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff811ebea9)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff818761ba)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff81886fec)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff811f6f29)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8190d27a)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff8191df5c)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
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
In kernel/bpf/cpumap.c (ffffffff8120520f)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
```
In net/core/skbuff.c (ffffffff8192e3aa)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_expand_head
```
```
In net/core/dev.c (ffffffff8193f5e5)
Location: include/linux/skbuff.h:3752
Inline: True
Inline callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
</details>
</li>
</ul>

## Differences
