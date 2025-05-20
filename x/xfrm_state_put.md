# Function: <code>xfrm_state_put</code>

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
In net/ipv4/xfrm4_policy.c (ffffffff817af3dd)
Location: include/net/xfrm.h:811
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b1906)
Location: include/net/xfrm.h:811
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8d89)
Location: include/net/xfrm.h:811
Inline: True
Inline callers:
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
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb790)
Location: include/net/xfrm.h:811
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:__secpath_destroy
```
```
In net/ipv6/xfrm6_policy.c (ffffffff817fbf75)
Location: include/net/xfrm.h:811
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff817fcc50)
Location: include/net/xfrm.h:811
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/ipv4/xfrm4_policy.c (ffffffff8181c2e2)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181f8be)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81826cfd)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_delete_tunnel
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff818286b0)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:__secpath_destroy
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8186b84f)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff8186c598)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/ipv4/xfrm4_policy.c (ffffffff8184dba2)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8185111e)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff818584dd)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a090)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:__secpath_destroy
```
```
In net/ipv6/xfrm6_policy.c (ffffffff8189e6af)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff8189f3a8)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/ipv4/xfrm4_policy.c (ffffffff8187161a)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81876011)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff8187c36d)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff8187de70)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:__secpath_destroy
```
```
In net/ipv6/xfrm6_policy.c (ffffffff818c4bec)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff818c58f5)
Location: include/net/xfrm.h:844
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/ipv4/xfrm4_policy.c (ffffffff818f2010)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f710c)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff818fd09d)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff818fed00)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:__secpath_destroy
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81948238)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81948c0f)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/ipv4/xfrm4_policy.c (ffffffff8194889a)
Location: include/net/xfrm.h:851
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194d3fd)
Location: include/net/xfrm.h:851
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81953b1d)
Location: include/net/xfrm.h:851
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_input.c (ffffffff819557da)
Location: include/net/xfrm.h:851
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:__secpath_destroy
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a0df9)
Location: include/net/xfrm.h:851
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff819a1c99)
Location: include/net/xfrm.h:851
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff8189d186)
Location: include/net/xfrm.h:863
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff8197a56a)
Location: include/net/xfrm.h:863
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197eb29)
Location: include/net/xfrm.h:863
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff819879b2)
Location: include/net/xfrm.h:863
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7a19)
Location: include/net/xfrm.h:863
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff819d88cd)
Location: include/net/xfrm.h:863
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff818e7bff)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819e406f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e7aec)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff819f173e)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46a3f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a47132)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff8191a0df)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a1b06f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1eadc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2860e)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d5ef)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a7dce2)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff819ebfeb)
Location: include/net/xfrm.h:788
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0c4df)
Location: include/net/xfrm.h:788
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1165d)
Location: include/net/xfrm.h:788
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1ac69)
Location: include/net/xfrm.h:788
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b7859b)
Location: include/net/xfrm.h:788
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7881d)
Location: include/net/xfrm.h:788
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff819eb7fb)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b1a7ff)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1ff22)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81b29423)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
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
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b8750b)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b8778d)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff819d1deb)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81b0848f)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0de04)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17063)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b761bb)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81b7643d)
Location: include/net/xfrm.h:791
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff81a81a5a)
Location: include/net/xfrm.h:787
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81bcb39b)
Location: include/net/xfrm.h:787
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd09ce)
Location: include/net/xfrm.h:787
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb413)
Location: include/net/xfrm.h:787
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40c27)
Location: include/net/xfrm.h:787
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81c40ead)
Location: include/net/xfrm.h:787
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff81bf6255)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81d60ddb)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d66f49)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72190)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf347)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81ddf5de)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff81da4b35)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f2b68b)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f31b0e)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3dda2)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1597)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81fb188e)
Location: include/net/xfrm.h:807
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff81e137a5)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81f8b300)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f91106)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d6f2)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011c3d)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff82011f2f)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff81ed07d5)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff82052a00)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205ee7a)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve_one
```
```
In net/xfrm/xfrm_state.c (ffffffff8206aa52)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_state_bpf.c (ffffffff82075f35)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/xfrm/xfrm_state_bpf.c:bpf_xdp_xfrm_state_release
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0bdd)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff820e109f)
Location: include/net/xfrm.h:812
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffff800010bb25f8)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffff800010cd71dc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffff800010cdae24)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffff800010ce7d6c)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d4879c)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffff800010d48ffc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (c0cd0874)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (c0de0db8)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (c0de51ec)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (c0deeff8)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (c0e49ccc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (c0e4a428)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (c000000000c8a138)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_put
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (c000000000df6f10)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (c000000000dffdcc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (c000000000e09dec)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7d950)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (c000000000e7e43c)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffe0007434e6)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_put_sp
```
```
In net/ipv4/xfrm4_policy.c (ffffffe0008279cc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082c96e)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffe00083555c)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
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
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffe000881de6)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffe0008824bc)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff818ba0df)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819ba6ff)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff819be16c)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff819c7c9e)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1cc7f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a1d372)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff8187402f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff819774ef)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197af5c)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81984a8e)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9a3f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff819da132)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff8190b0df)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a2517f)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a28bec)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3271e)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a876ff)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a87df2)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
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
In net/core/skbuff.c (ffffffff8192c1df)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_del
```
```
In net/ipv4/xfrm4_policy.c (ffffffff81a305ef)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv4/xfrm4_policy.c:xfrm4_dst_destroy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a3420d)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
  - net/xfrm/xfrm_policy.c:xfrm_tmpl_resolve
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3e023)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a942cf)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_destroy
```
```
In net/ipv6/xfrm6_input.c (ffffffff81a94a21)
Location: include/net/xfrm.h:790
Inline: True
Inline callers:
  - net/ipv6/xfrm6_input.c:xfrm6_input_addr
```
</details>
</li>
</ul>

## Differences
