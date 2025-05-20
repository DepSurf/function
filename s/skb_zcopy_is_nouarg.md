# Function: <code>skb_zcopy_is_nouarg</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a053c)
Location: include/linux/skbuff.h:1353
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
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
In net/core/skbuff.c (ffffffff818eb57e)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818fbc42)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81929970)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffff8198c720)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81991625)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8199e6c4)
Location: include/linux/skbuff.h:1441
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8191d6de)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8192e212)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195bfd9)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffff819c308f)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819c81ff)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819d51bf)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff819efbd3)
Location: include/linux/skbuff.h:1444
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a0234b)
Location: include/linux/skbuff.h:1444
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a30f59)
Location: include/linux/skbuff.h:1444
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/tcp.c (ffffffff81aae690)
Location: include/linux/skbuff.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ab4fd2)
Location: include/linux/skbuff.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ac0249)
Location: include/linux/skbuff.h:1444
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff819ef87c)
Location: include/linux/skbuff.h:1465
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a02b4b)
Location: include/linux/skbuff.h:1465
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a333e9)
Location: include/linux/skbuff.h:1465
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/tcp.c (ffffffff81ab8968)
Location: include/linux/skbuff.h:1465
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81ac00fc)
Location: include/linux/skbuff.h:1465
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81acbca3)
Location: include/linux/skbuff.h:1465
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff819d8025)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff819e7142)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a1a190)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/tcp.c (ffffffff81aa3c5b)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81aa712d)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81ab6f12)
Location: include/linux/skbuff.h:1482
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff81a87e75)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81a97af2)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81acc429)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
```
```
In net/ipv4/tcp.c (ffffffff81b5fe0b)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81b6372a)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff81b740ff)
Location: include/linux/skbuff.h:1495
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_collapse_retrans
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
In net/core/skbuff.c (ffffffff81bfd404)
Location: include/linux/skbuff.h:1844
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81c11768)
Location: include/linux/skbuff.h:1844
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c490f0)
Location: include/linux/skbuff.h:1844
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff81da9358)
Location: include/linux/skbuff.h:1694
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
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
In net/core/skbuff.c (ffffffff81e17f9c)
Location: include/linux/skbuff.h:1723
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed537d)
Location: include/linux/skbuff.h:1730
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
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
In net/core/skbuff.c (ffff800010bb808c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffff800010bcd67c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c01508)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffff800010c75e5c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffff800010c7bcdc)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffff800010c87e18)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (c0cd4c68)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (c0ce78e0)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d18614)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (c0d8450c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c0d89c64)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c0d97194)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (c000000000c8ffac)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (c000000000ca744c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000ce9000)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (c000000000d7d7ac)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (c000000000d8495c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (c000000000d94b6c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffe00074798c)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffe000756dd4)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077ffd2)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffe0007d9062)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffe0007dde52)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffe0007e90ec)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff818bd6de)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff818ce212)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818fbfa9)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffff81962eff)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff8196806f)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8197502f)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8187761e)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81888332)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5dd9)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffff8191c9ef)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff81921b5f)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff8192eaef)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8190e6de)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff8191f212)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194cfd9)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffff819cd6cf)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819d283f)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819df7ff)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
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
In net/core/skbuff.c (ffffffff8192f80e)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:__pskb_pull_tail
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_copy_ubufs
  - net/core/skbuff.c:skb_release_data
```
```
In net/core/dev.c (ffffffff81940f72)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8196e999)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
```
In net/ipv4/tcp.c (ffffffff819d725f)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_write_queue_purge
  - net/ipv4/tcp.c:tcp_write_queue_purge
```
```
In net/ipv4/tcp_input.c (ffffffff819dc3df)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_clean_rtx_queue
  - net/ipv4/tcp_input.c:tcp_shifted_skb
```
```
In net/ipv4/tcp_output.c (ffffffff819e94af)
Location: include/linux/skbuff.h:1438
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_synack
  - net/ipv4/tcp_output.c:__tcp_retransmit_skb
  - net/ipv4/tcp_output.c:tcp_mtu_probe
```
</details>
</li>
</ul>

## Differences
