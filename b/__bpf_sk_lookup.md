# Function: <code>__bpf_sk_lookup</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int __bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8d20)
Location: net/core/filter.c:5069
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff818d8d20-ffffffff818d8e7e: __bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81926fb0)
Location: net/core/filter.c:5290
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff81926fb0-ffffffff81927021: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81959660)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff81959660-ffffffff819596c1: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81a2e6b5)
Location: net/core/filter.c:5426
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
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
In net/core/filter.c (ffffffff81a3041c)
Location: net/core/filter.c:5978
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
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
In net/core/filter.c (ffffffff81a1738c)
Location: net/core/filter.c:6080
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
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
In net/core/filter.c (ffffffff81acaa69)
Location: net/core/filter.c:6204
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6512
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff81c48b10-ffffffff81c48bf7: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
ffffffff81f03ef2-ffffffff81f03f2e: __bpf_sk_lookup.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6524
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff81dfde60-ffffffff81dfdf2e: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
ffffffff820ac66a-ffffffff820ac6a6: __bpf_sk_lookup.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *__bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6604
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81e6eac0-ffffffff81e6eba1: __bpf_sk_lookup (STB_LOCAL)
ffffffff8212dcd8-ffffffff8212dd0d: __bpf_sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *__bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, struct net *caller_net, u32 ifindex, u8 proto, u64 netns_id, u64 flags, int sdif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6694
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_udp
  - net/core/filter.c:bpf_tc_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81f2e120-ffffffff81f2e201: __bpf_sk_lookup (STB_LOCAL)
ffffffff8220fa3e-ffffffff8220fa73: __bpf_sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffff800010bfacb8)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffff800010bfacb8-ffff800010bfad70: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (c0d14700)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
c0d14700-c0d14788: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (c000000000ce3070)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
c000000000ce3070-c000000000ce3140: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffe00077c8aa)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffe00077c8aa-ffffffe00077c93c: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818f9630)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff818f9630-ffffffff818f9691: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b3460)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff818b3460-ffffffff818b34c1: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff8194a660)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff8194a660-ffffffff8194a6c1: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff8196bf70)
Location: net/core/filter.c:5299
Inline: True
Direct callers:
  - net/core/filter.c:bpf_sock_addr_sk_lookup_udp
  - net/core/filter.c:bpf_sock_addr_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_tcp
  - net/core/filter.c:bpf_xdp_sk_lookup_udp
```
**Symbols:**

```
ffffffff8196bf70-ffffffff8196bfd1: __bpf_sk_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
