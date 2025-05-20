# Function: <code>bpf_push_mac_rcsum</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179db3c)
Location: net/core/filter.c:1364
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cc59c)
Location: net/core/filter.c:1375
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff817eb8bc)
Location: net/core/filter.c:1400
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818666ec)
Location: net/core/filter.c:1421
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5405)
Location: net/core/filter.c:1633
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dba65)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819290d5)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195b7b5)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e9b5)
Location: net/core/filter.c:1641
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30625)
Location: net/core/filter.c:1671
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a176c5)
Location: net/core/filter.c:1671
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac8c55)
Location: net/core/filter.c:1672
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c45a95)
Location: net/core/filter.c:1673
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff81df9cf5)
Location: net/core/filter.c:1675
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff81e6bae5)
Location: net/core/filter.c:1675
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff81f2abc5)
Location: net/core/filter.c:1682
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect_neigh
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfc9b0)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d18198)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce7ee4)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f7c8)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb785)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b55b5)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194c7b5)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196e175)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_pop
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:bpf_skb_vlan_push
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>

## Differences
