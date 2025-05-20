# Function: <code>bpf_ipv4_fib_lookup</code>

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
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b40f0)
Location: net/core/filter.c:4182
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818b40f0-ffffffff818b4472: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d98a0)
Location: net/core/filter.c:4467
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818d98a0-ffffffff818d9c1f: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192a260)
Location: net/core/filter.c:4605
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8192a260-ffffffff8192a702: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195c5f0)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8195c5f0-ffffffff8195ca92: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ddd0)
Location: net/core/filter.c:4740
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81a2ddd0-ffffffff81a2e25a: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fd10)
Location: net/core/filter.c:5283
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81a2fd10-ffffffff81a301da: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a16e60)
Location: net/core/filter.c:5261
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81a16e60-ffffffff81a17312: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5385
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81ac90d0-ffffffff81ac95d5: bpf_ipv4_fib_lookup (STB_LOCAL)
ffffffff81d37211-ffffffff81d372a3: bpf_ipv4_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5694
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81c46010-ffffffff81c46518: bpf_ipv4_fib_lookup (STB_LOCAL)
ffffffff81f03b61-ffffffff81f03c11: bpf_ipv4_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5708
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81dfa4e0-ffffffff81dfa9f5: bpf_ipv4_fib_lookup (STB_LOCAL)
ffffffff820ac1ef-ffffffff820ac29f: bpf_ipv4_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5758
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81e6e090-ffffffff81e6e60f: bpf_ipv4_fib_lookup (STB_LOCAL)
ffffffff8212dbf3-ffffffff8212dca6: bpf_ipv4_fib_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5832
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff81f2d960-ffffffff81f2df14: bpf_ipv4_fib_lookup (STB_LOCAL)
ffffffff8220f983-ffffffff8220fa3e: bpf_ipv4_fib_lookup.cold (STB_LOCAL)
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
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfe428)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffff800010bfe428-ffff800010bfe824: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d18b9c)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
c0d18b9c-c0d18fd4: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce6040)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
c000000000ce6040-c000000000ce65ac: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007804c2)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffe0007804c2-ffffffe00078087e: bpf_ipv4_fib_lookup (STB_LOCAL)
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
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fc5c0)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818fc5c0-ffffffff818fca62: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b63f0)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff818b63f0-ffffffff818b6892: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194d5f0)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8194d5f0-ffffffff8194da92: bpf_ipv4_fib_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_ipv4_fib_lookup(struct net *net, struct bpf_fib_lookup *params, u32 flags, bool check_mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196efb0)
Location: net/core/filter.c:4614
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_fib_lookup
  - net/core/filter.c:bpf_xdp_fib_lookup
```
**Symbols:**

```
ffffffff8196efb0-ffffffff8196f46d: bpf_ipv4_fib_lookup (STB_LOCAL)
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
