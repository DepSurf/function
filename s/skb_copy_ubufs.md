# Function: <code>skb_copy_ubufs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817065f0)
Location: net/core/skbuff.c:949
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
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
**Symbols:**

```
ffffffff817065f0-ffffffff81706830: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176e920)
Location: net/core/skbuff.c:954
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
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
**Symbols:**

```
ffffffff8176e920-ffffffff8176ec03: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179bde0)
Location: net/core/skbuff.c:954
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
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
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8179bde0-ffffffff8179c0c2: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817ba140)
Location: net/core/skbuff.c:956
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
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
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff817ba140-ffffffff817ba393: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81834100)
Location: net/core/skbuff.c:1173
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81834100-ffffffff818346bc: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187e890)
Location: net/core/skbuff.c:1174
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8187e890-ffffffff8187ee3a: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189f1a0)
Location: net/core/skbuff.c:1183
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8189f1a0-ffffffff8189f759: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e99c0)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff818e99c0-ffffffff818e9f97: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191bb30)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8191bb30-ffffffff8191c111: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ee500)
Location: net/core/skbuff.c:1341
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff819ee500-ffffffff819eea65: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ee1a0)
Location: net/core/skbuff.c:1352
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff819ee1a0-ffffffff819ee703: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d3bd0)
Location: net/core/skbuff.c:1394
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff819d3bd0-ffffffff819d410d: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a838d0)
Location: net/core/skbuff.c:1415
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff81a838d0-ffffffff81a83e29: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf90d0)
Location: net/core/skbuff.c:1409
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff81bf90d0-ffffffff81bf9771: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da7f20)
Location: net/core/skbuff.c:1607
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff81da7f20-ffffffff81da85bb: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1751
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff8212c216-ffffffff8212c297: skb_copy_ubufs.cold (STB_LOCAL)
ffffffff81e16a10-ffffffff81e1725f: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:1839
Inline: False
Direct callers:
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:__skb_tstamp_tx
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb2
  - net/core/filter.c:__bpf_redirect_no_mac
```
**Symbols:**

```
ffffffff8220def6-ffffffff8220df77: skb_copy_ubufs.cold (STB_LOCAL)
ffffffff81ed3e20-ffffffff81ed465f: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb6150)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffff800010bb6150-ffff800010bb66d8: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd308c)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
c0cd308c-c0cd3578: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8d730)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
c000000000c8d730-c000000000c8dea8: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000745f7c)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffe000745f7c-ffffffe000746430: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818bbb30)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff818bbb30-ffffffff818bc111: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81875a70)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff81875a70-ffffffff81876051: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190cb30)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8190cb30-ffffffff8190d111: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int skb_copy_ubufs(struct sk_buff *skb, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192dc70)
Location: net/core/skbuff.c:1342
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_net_xmit
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:pskb_carve
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_clone
  - net/core/skbuff.c:skb_zerocopy_clone
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
  - net/core/dev.c:dev_queue_xmit_nit
  - net/core/dev.c:__dev_forward_skb
  - net/core/filter.c:__bpf_redirect
```
**Symbols:**

```
ffffffff8192dc70-ffffffff8192e24a: skb_copy_ubufs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
