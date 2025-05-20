# Function: <code>bpf_ipv6_fib_lookup</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b4ab0)
Location: net/core/filter.c:4286
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818b4ab0-ffffffff818b4ed7: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818da670)
Location: net/core/filter.c:4571
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818da670-ffffffff818daa97: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81929dd0)
Location: net/core/filter.c:4720
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81929dd0-ffffffff8192a254: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195c160)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8195c160-ffffffff8195c5e4: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ff00)
Location: net/core/filter.c:4856
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81a2ff00-ffffffff81a30376: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a31c00)
Location: net/core/filter.c:5400
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81a31c00-ffffffff81a32080: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a18a70)
Location: net/core/filter.c:5380
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81a18a70-ffffffff81a18f1c: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5504
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81aca280-ffffffff81aca739: bpf_ipv6_fib_lookup (STB_LOCAL)
ffffffff81d372eb-ffffffff81d3730f: bpf_ipv6_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5813
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81c47680-ffffffff81c47b4b: bpf_ipv6_fib_lookup (STB_LOCAL)
ffffffff81f03cc1-ffffffff81f03ce6: bpf_ipv6_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5827
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81dfbd50-ffffffff81dfc22d: bpf_ipv6_fib_lookup (STB_LOCAL)
ffffffff820ac35e-ffffffff820ac383: bpf_ipv6_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5891
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81e6f840-ffffffff81e6fdb0: bpf_ipv6_fib_lookup (STB_LOCAL)
ffffffff8212ddce-ffffffff8212de01: bpf_ipv6_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5968
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81f2f010-ffffffff81f2f5bb: bpf_ipv6_fib_lookup (STB_LOCAL)
ffffffff8220fb34-ffffffff8220fb66: bpf_ipv6_fib_lookup.cold (STB_LOCAL)
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
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfe078)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffff800010bfe078-ffff800010bfe424: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d187b0)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
c0d187b0-c0d18b9c: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce5ac0)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
c000000000ce5ac0-c000000000ce6038: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000780138)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffe000780138-ffffffe0007804c2: bpf_ipv6_fib_lookup (STB_LOCAL)
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
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fc130)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818fc130-ffffffff818fc5b4: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5f60)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818b5f60-ffffffff818b63e4: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194d160)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8194d160-ffffffff8194d5e4: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_ipv6_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196eb20)
Location: net/core/filter.c:4729
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8196eb20-ffffffff8196efa4: bpf_ipv6_fib_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
