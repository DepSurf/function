# Function: <code>xdp_get_buff_len</code>

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
In net/core/filter.c (ffffffff81c3d727)
Location: include/net/xdp.h:149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df18d7)
Location: include/net/xdp.h:149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e74a04)
Location: include/net/xdp.h:153
Inline: True
Inline callers:
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
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
In net/core/filter.c (ffffffff81f341c4)
Location: include/net/xdp.h:152
Inline: True
Inline callers:
  - net/core/filter.c:bpf_dynptr_from_xdp
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_get_buff_len
```
```
In net/xdp/xsk.c (ffffffff8213fd45)
Location: include/net/xdp.h:152
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
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
