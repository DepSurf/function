# Function: <code>__skb_grow</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb5e2)
Location: include/linux/skbuff.h:2360
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eadf8)
Location: include/linux/skbuff.h:2409
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (ffffffff816ff26b)
Location: include/linux/skbuff.h:2496
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff818678d3)
Location: include/linux/skbuff.h:2496
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (ffffffff8173e9e0)
Location: include/linux/skbuff.h:2508
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff818b56f7)
Location: include/linux/skbuff.h:2508
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff8176264a)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff818dc569)
Location: include/linux/skbuff.h:2584
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (ffffffff817a038d)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff81929679)
Location: include/linux/skbuff.h:2670
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (ffffffff817c533d)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff81955d44)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff8188b518)
Location: include/linux/skbuff.h:2707
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81a2d5b4)
Location: include/linux/skbuff.h:2707
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff818996bc)
Location: include/linux/skbuff.h:2733
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81a2ef74)
Location: include/linux/skbuff.h:2733
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff8187bb2c)
Location: include/linux/skbuff.h:2749
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81a19201)
Location: include/linux/skbuff.h:2749
Inline: True
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
In drivers/net/tun.c (ffffffff8190d05c)
Location: include/linux/skbuff.h:2778
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81ac74b1)
Location: include/linux/skbuff.h:2778
Inline: True
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
In drivers/net/tun.c (ffffffff81a62a4e)
Location: include/linux/skbuff.h:3147
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81c43d38)
Location: include/linux/skbuff.h:3147
Inline: True
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
In drivers/net/tun.c (ffffffff81beef17)
Location: include/linux/skbuff.h:3041
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81df7f28)
Location: include/linux/skbuff.h:3041
Inline: True
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
In drivers/net/tun.c (ffffffff81c46fb7)
Location: include/linux/skbuff.h:3095
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81e6760a)
Location: include/linux/skbuff.h:3095
Inline: True
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
In drivers/net/tun.c (ffffffff81cfc8d3)
Location: include/linux/skbuff.h:3102
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
```
In net/core/filter.c (ffffffff81f267ca)
Location: include/linux/skbuff.h:3102
Inline: True
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
In drivers/net/tun.c (ffff8000109e05b8)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffff800010bfd134)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (c0ac4728)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (c0d17730)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (c000000000aa195c)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (c000000000ce55fc)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (ffffffe00062a476)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffe00077fb3a)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
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
In drivers/net/tun.c (ffffffff81789e1d)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff818f5d14)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff8176976d)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff818afb44)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff817ba1bd)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff81946d44)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
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
In drivers/net/tun.c (ffffffff817d26bd)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/filter.c (ffffffff81968654)
Location: include/linux/skbuff.h:2684
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_grow_rcsum
```
</details>
</li>
</ul>

## Differences
