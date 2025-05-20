# Function: <code>xdp_frame_has_frags</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c5128d)
Location: include/net/xdp.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
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
In kernel/bpf/devmap.c (ffffffff8131d0f6)
Location: include/net/xdp.h:177
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In net/core/xdp.c (ffffffff81e06a2a)
Location: include/net/xdp.h:177
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
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
In kernel/bpf/devmap.c (ffffffff8134ced4)
Location: include/net/xdp.h:181
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In drivers/net/virtio_net.c (ffffffff81c4f45a)
Location: include/net/xdp.h:181
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
```
In net/core/xdp.c (ffffffff81e78347)
Location: include/net/xdp.h:181
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
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
In kernel/bpf/devmap.c (ffffffff81374401)
Location: include/net/xdp.h:180
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:is_valid_dst
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
```
```
In drivers/net/virtio_net.c (ffffffff81d0515a)
Location: include/net/xdp.h:180
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_xdp_xmit
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
  - drivers/net/virtio_net.c:free_old_xmit_skbs
```
```
In net/core/xdp.c (ffffffff81f38307)
Location: include/net/xdp.h:180
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
