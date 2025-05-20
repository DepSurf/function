# Function: <code>__xfrm_state_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817b7410)
Location: net/xfrm/xfrm_state.c:501
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_input.c:__secpath_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff817b7410-ffffffff817b74a0: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81824450)
Location: net/xfrm/xfrm_state.c:502
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_input.c:__secpath_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81824450-ffffffff818244e0: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81856080)
Location: net/xfrm/xfrm_state.c:513
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_input.c:__secpath_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81856080-ffffffff81856103: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81879ce0)
Location: net/xfrm/xfrm_state.c:586
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_input.c:__secpath_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81879ce0-ffffffff81879d54: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818fa740)
Location: net/xfrm/xfrm_state.c:594
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_input.c:__secpath_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff818fa740-ffffffff818fa7b4: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81951240)
Location: net/xfrm/xfrm_state.c:595
Inline: False
Direct callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_input.c:__secpath_destroy
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81951240-ffffffff819512b4: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81984be0)
Location: net/xfrm/xfrm_state.c:601
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81984be0-ffffffff81984c69: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819eed19)
Location: net/xfrm/xfrm_state.c:639
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff819f43bb-ffffffff819f43d4: __xfrm_state_destroy.cold (STB_LOCAL)
ffffffff819eece0-ffffffff819eed7b: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a25bc0)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81a25bc0-ffffffff81a25c4f: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b17620)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81b17620-ffffffff81b176b3: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b256e0)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81b256e0-ffffffff81b25773: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b13200)
Location: net/xfrm/xfrm_state.c:640
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81b13200-ffffffff81b13293: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd7100)
Location: net/xfrm/xfrm_state.c:662
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81bd7100-ffffffff81bd7193: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6daf0)
Location: net/xfrm/xfrm_state.c:663
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81d6daf0-ffffffff81d6db9e: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f39100)
Location: net/xfrm/xfrm_state.c:686
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81f39100-ffffffff81f391ae: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f98c40)
Location: net/xfrm/xfrm_state.c:686
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81f98c40-ffffffff81f98cee: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82065fa0)
Location: net/xfrm/xfrm_state.c:686
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_xfrm_state_release
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff82065fa0-ffffffff8206604e: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce5e10)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffff800010ce5e10-ffff800010ce5f34: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c0dec860)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
c0dec860-c0dec918: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c000000000e065a0)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
c000000000e065a0-c000000000e066a0: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000831930)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:skb_ext_put_sp
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffe000831930-ffffffe0008319d8: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819c5250)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff819c5250-ffffffff819c52df: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81982040)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81982040-ffffffff819820cf: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a2fcd0)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81a2fcd0-ffffffff81a2fd5f: __xfrm_state_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __xfrm_state_destroy(struct xfrm_state *x, bool sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3b670)
Location: net/xfrm/xfrm_state.c:641
Inline: True
Direct callers:
  - net/core/skbuff.c:__skb_ext_del
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
**Symbols:**

```
ffffffff81a3b670-ffffffff81a3b6ff: __xfrm_state_destroy (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool sync</code>
</li>
</ul>
</details>
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
