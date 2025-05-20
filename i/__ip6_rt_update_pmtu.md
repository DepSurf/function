# Function: <code>__ip6_rt_update_pmtu</code>

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
In net/ipv6/route.c (ffffffff817d6c90)
Location: net/ipv6/route.c:1340
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff817d6c90-ffffffff817d6e80: __ip6_rt_update_pmtu.part.47 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff818455b0)
Location: net/ipv6/route.c:1351
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81845320-ffffffff8184550f: __ip6_rt_update_pmtu.part.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81877090)
Location: net/ipv6/route.c:1359
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81877090-ffffffff818772a8: __ip6_rt_update_pmtu (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff8189c662)
Location: net/ipv6/route.c:1391
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff8189c330-ffffffff8189c584: __ip6_rt_update_pmtu.part.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191c300)
Location: net/ipv6/route.c:2070
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff8191c300-ffffffff8191c600: __ip6_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819749c0)
Location: net/ipv6/route.c:2313
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff819749c0-ffffffff81974b6a: __ip6_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819aa5e0)
Location: net/ipv6/route.c:2304
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff819aa5e0-ffffffff819aa787: __ip6_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a17930)
Location: net/ipv6/route.c:2693
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a17930-ffffffff81a17be2: __ip6_rt_update_pmtu (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a4e8d7)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a4e580-ffffffff81a4e82b: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b45f60)
Location: net/ipv6/route.c:2721
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b45f60-ffffffff81b4616f: __ip6_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b54a90)
Location: net/ipv6/route.c:2704
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b54a90-ffffffff81b54c97: __ip6_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b42450)
Location: net/ipv6/route.c:2713
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b42450-ffffffff81b42725: __ip6_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2843
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81c07b30-ffffffff81c07e72: __ip6_rt_update_pmtu (STB_LOCAL)
ffffffff81d3fd88-ffffffff81d3fdb8: __ip6_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2839
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81da27d0-ffffffff81da2b47: __ip6_rt_update_pmtu (STB_LOCAL)
ffffffff81f0c826-ffffffff81f0c856: __ip6_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2839
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81f71ba0-ffffffff81f71f17: __ip6_rt_update_pmtu (STB_LOCAL)
ffffffff820b3e77-ffffffff820b3ea7: __ip6_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2838
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81fd1c80-ffffffff81fd2009: __ip6_rt_update_pmtu (STB_LOCAL)
ffffffff82134f4c-ffffffff82134f75: __ip6_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (0)
Location: net/ipv6/route.c:2840
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff8209f210-ffffffff8209f599: __ip6_rt_update_pmtu (STB_LOCAL)
ffffffff82216930-ffffffff82216959: __ip6_rt_update_pmtu.cold (STB_LOCAL)
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
In net/ipv6/route.c (ffff800010d12740)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffff800010d12410-ffff800010d12654: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __ip6_rt_update_pmtu(struct dst_entry *dst, const struct sock *sk, const struct ipv6hdr *iph, u32 mtu, bool confirm_neigh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e18094)
Location: net/ipv6/route.c:2699
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
c0e18094-c0e18338: __ip6_rt_update_pmtu (STB_LOCAL)
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
In net/ipv6/route.c (c000000000e3ebd4)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
c000000000e3e7e0-c000000000e3eae4: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffe000858a6c)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffe000858796-ffffffe00085898a: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff819edf67)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff819edc10-ffffffff819edebb: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff819aad27)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff819aa9d0-ffffffff819aac7b: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a589e7)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a58690-ffffffff81a5893b: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81a64ba7)
Location: net/ipv6/route.c:2699
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
Direct callers:
  - net/ipv6/route.c:ip6_update_pmtu
  - net/ipv6/route.c:ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a64840-ffffffff81a64afa: __ip6_rt_update_pmtu.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
