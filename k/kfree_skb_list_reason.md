# Function: <code>kfree_skb_list_reason</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list_reason(struct sk_buff *segs, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfd489)
Location: net/core/skbuff.c:782
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81bf8290-ffffffff81bf82d0: kfree_skb_list_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kfree_skb_list_reason(struct sk_buff *segs, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dac305)
Location: net/core/skbuff.c:960
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
Direct callers:
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81da7980-ffffffff81da79c0: kfree_skb_list_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfree_skb_list_reason(struct sk_buff *segs, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e161b0)
Location: net/core/skbuff.c:1090
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81e161b0-ffffffff81e16403: kfree_skb_list_reason (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfree_skb_list_reason(struct sk_buff *segs, enum skb_drop_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed35d0)
Location: net/core/skbuff.c:1176
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:___pskb_trim
  - net/core/skbuff.c:skb_release_data
  - net/core/dev.c:__dev_direct_xmit
  - net/core/dev.c:__dev_queue_xmit
  - net/core/dev.c:__dev_xmit_skb
  - net/core/dev.c:__dev_xmit_skb
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/netfilter.c:br_ip6_fragment
  - net/ipv6/ip6_offload.c:ipv6_gso_segment
```
**Symbols:**

```
ffffffff81ed35d0-ffffffff81ed3823: kfree_skb_list_reason (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
