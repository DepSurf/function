# Function: <code>xdp_get_shared_info_from_buff</code>

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
In net/core/filter.c (ffffffff81c3d7a4)
Location: include/net/xdp.h:144
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81c51fe4)
Location: include/net/xdp.h:144
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
```
```
In net/bpf/test_run.c (ffffffff81cb5784)
Location: include/net/xdp.h:144
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In net/core/filter.c (ffffffff81df1954)
Location: include/net/xdp.h:144
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81e07264)
Location: include/net/xdp.h:144
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
```
```
In net/bpf/test_run.c (ffffffff81e73c54)
Location: include/net/xdp.h:144
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/virtio_net.c (ffffffff81c555a0)
Location: include/net/xdp.h:148
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In net/core/filter.c (ffffffff81e74a36)
Location: include/net/xdp.h:148
Inline: True
Inline callers:
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81e79a58)
Location: include/net/xdp.h:148
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_return_buff
```
```
In net/bpf/test_run.c (ffffffff81ecf9c3)
Location: include/net/xdp.h:148
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
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
In drivers/net/virtio_net.c (ffffffff81d0bc3b)
Location: include/net/xdp.h:147
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:receive_mergeable_xdp
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
```
In net/core/filter.c (ffffffff81f341f6)
Location: include/net/xdp.h:147
Inline: True
Inline callers:
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/core/xdp.c (ffffffff81f392eb)
Location: include/net/xdp.h:147
Inline: True
Inline callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:__xdp_return
```
```
In net/bpf/test_run.c (ffffffff81f93313)
Location: include/net/xdp.h:147
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
```
```
In net/xdp/xsk.c (ffffffff8213ff3e)
Location: include/net/xdp.h:147
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
