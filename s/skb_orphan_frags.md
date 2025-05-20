# Function: <code>skb_orphan_frags</code>

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
In drivers/net/tun.c (ffffffff815ee8ca)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8170683c)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
```
```
In net/core/dev.c (ffffffff81717bac)
Location: include/linux/skbuff.h:2231
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_hard_start_xmit
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
In drivers/net/tun.c (ffffffff8164d4a6)
Location: include/linux/skbuff.h:2366
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8176ef5c)
Location: include/linux/skbuff.h:2366
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81782687)
Location: include/linux/skbuff.h:2366
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
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
In drivers/net/tun.c (ffffffff8167f1c6)
Location: include/linux/skbuff.h:2402
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff8179c44c)
Location: include/linux/skbuff.h:2402
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff817aff71)
Location: include/linux/skbuff.h:2402
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817cbcac)
Location: include/linux/skbuff.h:2402
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In drivers/net/tun.c (ffffffff816943e4)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_net_xmit
```
```
In net/core/skbuff.c (ffffffff817bd39c)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff817ce7d0)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:__netif_receive_skb_core
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff817ea746)
Location: include/linux/skbuff.h:2451
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff8183575c)
Location: include/linux/skbuff.h:2538
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff818456d6)
Location: include/linux/skbuff.h:2538
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81865e76)
Location: include/linux/skbuff.h:2538
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff8187fb70)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff8188ecb5)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b3ee7)
Location: include/linux/skbuff.h:2550
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff818a07e1)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff818afd55)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818dc6de)
Location: include/linux/skbuff.h:2626
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff818eb225)
Location: include/linux/skbuff.h:2712
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff818fbba5)
Location: include/linux/skbuff.h:2712
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff819297ec)
Location: include/linux/skbuff.h:2712
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff8191d385)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff8192e175)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8195be4c)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff819efa47)
Location: include/linux/skbuff.h:2749
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81a022c5)
Location: include/linux/skbuff.h:2749
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a30ef9)
Location: include/linux/skbuff.h:2749
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff819ef6fa)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81a02ace)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff81a33389)
Location: include/linux/skbuff.h:2775
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff819d7eb9)
Location: include/linux/skbuff.h:2791
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff819e70c6)
Location: include/linux/skbuff.h:2791
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81a1a123)
Location: include/linux/skbuff.h:2791
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff81a87d09)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81a97a76)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81acc3bc)
Location: include/linux/skbuff.h:2820
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff81bfd14c)
Location: include/linux/skbuff.h:3189
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81c1165e)
Location: include/linux/skbuff.h:3189
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81c48fcd)
Location: include/linux/skbuff.h:3189
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff81dac0bc)
Location: include/linux/skbuff.h:3083
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81dc120e)
Location: include/linux/skbuff.h:3083
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81dfd975)
Location: include/linux/skbuff.h:3083
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffffffff81e1bebe)
Location: include/linux/skbuff.h:3137
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81e3102e)
Location: include/linux/skbuff.h:3137
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81e6eea5)
Location: include/linux/skbuff.h:3137
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In drivers/net/netkit.c (ffffffff81ce5202)
Location: include/linux/skbuff.h:3144
Inline: True
Inline callers:
  - drivers/net/netkit.c:netkit_xmit
```
```
In net/core/skbuff.c (ffffffff81ed95be)
Location: include/linux/skbuff.h:3144
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81eed53e)
Location: include/linux/skbuff.h:3144
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb2
```
```
In net/core/filter.c (ffffffff81f2e505)
Location: include/linux/skbuff.h:3144
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/skbuff.c (ffff800010bb7d54)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffff800010bcd5fc)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffff800010c013ac)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (c0cd4944)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (c0ce785c)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c0d184c0)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (c000000000c8fb64)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (c000000000ca73a4)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (c000000000ce8ddc)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffe0007476f2)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffe000756d66)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffe00077fe66)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff818bd385)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff818ce175)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818fbe1c)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff818772c5)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81888295)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff818b5c4c)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff8190e385)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff8191f175)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8194ce4c)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
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
In net/core/skbuff.c (ffffffff8192f4b5)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_clone
```
```
In net/core/dev.c (ffffffff81940ed5)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/dev.c:__dev_forward_skb
```
```
In net/core/filter.c (ffffffff8196e80c)
Location: include/linux/skbuff.h:2726
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>

## Differences
