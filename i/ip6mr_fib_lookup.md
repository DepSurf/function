# Function: <code>ip6mr_fib_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff817f8af0)
Location: net/ipv6/ip6mr.c:139
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
  - net/ipv6/ip6mr.c:mroute6_socket
  - net/ipv6/ip6mr.c:ip6_mr_input
```
**Symbols:**

```
ffffffff817f8af0-ffffffff817f8b6a: ip6mr_fib_lookup.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818682e0)
Location: net/ipv6/ip6mr.c:139
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818682e0-ffffffff8186835a: ip6mr_fib_lookup.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8189b130)
Location: net/ipv6/ip6mr.c:139
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8189b130-ffffffff8189b1aa: ip6mr_fib_lookup.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff818c0d90)
Location: net/ipv6/ip6mr.c:140
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff818c0d90-ffffffff818c0e09: ip6mr_fib_lookup.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81943fb0)
Location: net/ipv6/ip6mr.c:140
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81943fb0-ffffffff81944029: ip6mr_fib_lookup.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8199caf0)
Location: net/ipv6/ip6mr.c:130
Inline: True
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8199caf0-ffffffff8199cb71: ip6mr_fib_lookup.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d3010)
Location: net/ipv6/ip6mr.c:135
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819d3010-ffffffff819d30b0: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a42030)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a42030-ffffffff81a420cf: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a78c90)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a78c90-ffffffff81a78d2f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b73470)
Location: net/ipv6/ip6mr.c:132
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81b73470-ffffffff81b7350f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b821a0)
Location: net/ipv6/ip6mr.c:132
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81b821a0-ffffffff81b8223f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81b70dd0)
Location: net/ipv6/ip6mr.c:132
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81b70dd0-ffffffff81b70e6f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81c3afe0)
Location: net/ipv6/ip6mr.c:132
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81c3afe0-ffffffff81c3b07f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81dd8fd0)
Location: net/ipv6/ip6mr.c:132
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81dd8fd0-ffffffff81dd9084: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81faabc0)
Location: net/ipv6/ip6mr.c:139
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81faabc0-ffffffff81faac74: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff8200b350)
Location: net/ipv6/ip6mr.c:139
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff8200b350-ffffffff8200b404: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff820da350)
Location: net/ipv6/ip6mr.c:139
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff820da350-ffffffff820da404: ip6mr_fib_lookup (STB_LOCAL)
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
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffff800010d42468)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffff800010d42468-ffff800010d4250c: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c0e44d70)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c0e44d70-c0e44e18: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (c000000000e772a0)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
c000000000e772a0-c000000000e77370: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffe00087dad8)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffe00087dad8-ffffffe00087db54: ip6mr_fib_lookup (STB_LOCAL)
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
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a18320)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a18320-ffffffff81a183bf: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff819d50e0)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff819d50e0-ffffffff819d517f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a82da0)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a82da0-ffffffff81a82e3f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ip6mr_fib_lookup(struct net *net, struct flowi6 *flp6, struct mr_table **mrt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6mr.c (ffffffff81a8f670)
Location: net/ipv6/ip6mr.c:130
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mr_input
  - net/ipv6/ip6mr.c:mroute6_is_socket
  - net/ipv6/ip6mr.c:reg_vif_xmit
  - net/ipv6/ip6mr.c:pim6_rcv
```
**Symbols:**

```
ffffffff81a8f670-ffffffff81a8f70f: ip6mr_fib_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
