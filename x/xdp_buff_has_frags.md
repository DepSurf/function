# Function: <code>xdp_buff_has_frags</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d72a)
Location: include/net/xdp.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81c51fa5)
Location: include/net/xdp.h:88
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
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
In net/core/filter.c (ffffffff81df18da)
Location: include/net/xdp.h:88
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81e07225)
Location: include/net/xdp.h:88
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
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
In drivers/net/virtio_net.c (ffffffff81c555b8)
Location: include/net/xdp.h:92
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In net/core/filter.c (ffffffff81e74a0e)
Location: include/net/xdp.h:92
Inline: True
Inline callers:
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:xdp_do_redirect
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81e79a15)
Location: include/net/xdp.h:92
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
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
In drivers/net/virtio_net.c (ffffffff81d0bc53)
Location: include/net/xdp.h:91
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In net/core/filter.c (ffffffff81f341ce)
Location: include/net/xdp.h:91
Inline: True
Inline callers:
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81f39238)
Location: include/net/xdp.h:91
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:__xdp_return
```
```
In net/xdp/xsk.c (ffffffff8213fd45)
Location: include/net/xdp.h:91
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk.c:__xsk_rcv
  - net/xdp/xsk.c:__xsk_rcv
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
